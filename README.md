# arduino-mqtt

#lightsensor-publishについて
時雨堂さんのMQTTbrokerに対して、arduinoでanalogreadした値をpublishします。
実際の構成はlightsensorを使いましたが、analogreadしたものであれば流用可能です。
ライトを光らせる条件については、各環境に合わせて任意の値に変更してください。
MQTTbrokerは当初フリープランで利用していたため、接続先名は"lite..."となっています。
