# MBDFirstStudy
Arduino MEGAでモデルベース開発<br>
Arduino MEGAの周辺機能をMATLAB,Simulinkモデルで動かす。
## 機能とモデルファイル名
### Lチカ
▪️スイッチのレベルでLEDを点灯・消灯するモデル<br>
▪️ファイル名：led_switch/led_switch.slx<br>
<br>
### タイマーでLチカ
▪️定期的にLEDを点灯・消灯するモデル<br>
▪️ファイル名：timer/timer.slx<br>
<br>
### AD変換・PWM・シリアル送信
▪️AD変換・PWM・シリアル送信を行うモデル<br>
▪️ファイル名：serial_ad_pwm/serial_ad_pwm.slx<br>
<br>
## 開発環境
●MATLAB, Simulink R2019b<br>
●Arduino MEGA ※Arduino UNOでも可。<br>
<br>
## 開発環境 動作確認バージョン
●MATLAB, Simulink<br>
---------------------------------------------------------------------------------------------------<br>
・MATLAB バージョン: 9.7.0.1319299 (R2019b) Update 5<br>
・オペレーティング システム: Mac OS X  Version: 10.15.4 Build: 19E287 <br>
・Java バージョン: Java 1.8.0_202-b08 with Oracle Corporation Java HotSpot(TM) 64-Bit Server VM mixed mode<br>
---------------------------------------------------------------------------------------------------<br>
MATLAB                                                バージョン 9.7           (R2019b)<br>
Simulink                                              バージョン 10.0          (R2019b)<br>
<br>
●Simulink Support Package for Arduino Hardware バージョン19.2.2<br>
## ブレッドボード接続図
### Lチカ(led_switch/led_switch.slx)
![led_switch](led_switch_ブレッドボード.png)
<br>
### AD変換・PWM・シリアル送信(serial_ad_pwm/serial_ad_pwm.slx)
![serial_ad_pwm](serial_ad_pwm_3_ブレッドボード_2.png)
<br>
## 参考資料
[・モデルベース開発勉強会](https://www.slideshare.net/KoujiAbe/ss-230677824)
<br>
