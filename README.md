# arduino-mqtt

#lightsensor-publishについて
時雨堂さんのsango(MQTTbroker)に対して、arduinoでanalogreadした値をpublishします。
実際の構成はlightsensorを使いましたが、analogreadしたものであれば流用可能です。

・LEDを光らせる条件（magic namuber:800）については、LEDをON/OFFする閾値ですので、各環境に合わせて任意の値に変更してください。
・当初ライトプラン（lite）で利用していたため、接続先名は"lite..."となっています。
