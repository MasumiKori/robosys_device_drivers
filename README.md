# robosys_device_drivers
デバイスドライバを作成しLEDを点灯させる

## 動作環境
| | |
|:---|:---|
|Raspberry Pi|Raspberry Pi Model 3B+|
|os|RaspbianGNU/Linux 10 (buster)|
|kernel|Linux raspberrypi 4.19.75-v7+|

## 実行
$ echo <番号> /dev/myled0

|入力番号|LEDの動作|
|:---|:---|
|0|消灯|
|1|点灯|
|2|点滅|

