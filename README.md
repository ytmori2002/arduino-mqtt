# arduino-mqtt
arduinoからmqttにて通信を実施する際に用いたcode等をのせる予定です。
・arduinoからpublish
・arduinoで読み込んだ値を、windowsPCにてシリアル値を読み込みpublish（windowsPCをMQTTgatewayにみたてる）（近日UP予定）
（PCのcomポートにて受信した値をpublish）
・electronにてデスクトップアプリを作成（近日UP予定）

#lightsensor-publishについて
時雨堂さんのsango(MQTTbroker)に対して、arduinoでanalogreadした値をpublishします。
実際の構成はlightsensorを使いましたが、analogreadしたものであれば流用可能です。

・LEDを光らせる条件（magic namuber:800）については、LEDをON/OFFする閾値ですので、各環境に合わせて任意の値に変更してください。
・当初ライトプラン（lite）で利用していたため、接続先名は"lite..."となっています。

＃キーワード
・arduino,ethernetshild,時雨堂,sango,Paho,moswquitto,
・windows(7),macbookpro(2010mid),linux(ubuntu-desktop,32bit)
