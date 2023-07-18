


0.) СКАЧАЙ linuxdeployqt

1.) ОТКРОЙ ДОСТУП

chmod a+x /home/astra2/Desktop/deployment/bluetooth_comport_terminal-main/linuxdeployqt-continuous-x86_64.AppImage

2.) УСТАНОВИ
sudo apt-get install qttools5-dev-tools


3.)

-qmake='/usr/lib/qt5/bin/qmake'  не обязательно

/usr/lib/x86_64-linux-gnu/qt5/bin/qmake  не обязательно

/usr/lib/qt5/bin/qmake  не обязательно


ПОПРОБУЙ ЕСЛИ НЕ РОБИТ ДЕЛАЙ СЛЕДУЮЩУЮ  не обязательно
/home/astra2/Desktop/deployment/bluetooth_comport_terminal-main/linuxdeployqt-continuous-x86_64.AppImage /home/astra2/Desktop/test/bluetooth_comport_terminal-main/build-bluetooth-Desktop_Qt_5_12_2_MinGW_32_bit-Release/build-bluetooth-Desktop-Release/bluetooth


РАБОЧАЯ КОМАНДА НИЖЕ
/home/astra2/Desktop/deployment/bluetooth_comport_terminal-main/linuxdeployqt-continuous-x86_64.AppImage /home/astra2/Desktop/test/bluetooth_comport_terminal-main/build-bluetooth-Desktop_Qt_5_12_2_MinGW_32_bit-Release/build-bluetooth-Desktop-Release/bluetooth -verbose=2

ЧЕКНИ В ЧЕМ ТРАБЛ ЕС ЧЕ  не обязательно
/home/astra2/Desktop/deployment/bluetooth_comport_terminal-main/linuxdeployqt-continuous-x86_64.AppImage /home/astra2/Desktop/test/bluetooth_comport_terminal-main/build-bluetooth-Desktop_Qt_5_12_2_MinGW_32_bit-Release/build-bluetooth-Desktop-Release/bluetooth -appimage




4.)  не обязательно
astra2@astra2:~$ qmake -v
QMake version 3.1
Using Qt version 5.11.0 in /usr/lib/x86_64-linux-gnu


ЗАПУСКАЙ У СЕБЯ ЧЕРЕЗ ТЕРМИНАЛ AppRun 
НЕ ЗАБУДЬ chmod a+x
