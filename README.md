# ADB LOCAL HOST 
connect adb localhost pake termux
kalian harus download aplikasi termux 
[Download Termux](https://github.com/termux/termux-app/releases)
# COMMAND
install android-tools
```
pkg i android-tools
```
sambungkan hp kalian ke wifi
lalu masuk ke develover settings
dengan cara menekan 7× build id ditentang ponsel
setelah masuk ke developer options kalian cari wireless debugging lalu aktifkan pair device with code

kalo sudah kalian masuk termux 
lalu ketikan ip dan port yg ada di wireless debugging
```
adb pair ipadress&port
contoh 
adb pair 192.168.0.9:44989
```
setelah itu connect ke devicenya
```
adb connect ipadress
```
kalian bisa uninstall bloatware/ aplikasi bawaan di hp kalian dengan cara 
```
adb uninstall com.myAppPackage
```
kalian bisa liat package name aplikasi di info app
kalo gk ada kalian bisa install aplikasi [package name viewer 2.0](https://play.google.com/store/apps/details?id=com.csdroid.pkg)
