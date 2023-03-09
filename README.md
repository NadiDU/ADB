# ADB
ADB HW_1

 1. Отобразить подключенный девайс в консоли. **./adb devises**
 2. Вывести адрес приложения todolist в системе Android **./adb ‘pm list packages -l | finster todolost**
 3. Установить .apk файл приложения todolist на телефон с компьютера через  ADB **./adb install**
 4. Сделать скриншот запущенного приложения todolist и сразу скопировать на компьютер в одной команде. **./adb shell screencap storage/emulated/0/dDSIM/Nadya.png**
5. Вывести в консоль логи приложения todolist **./adb logcat** 
6. Вывести логи в текстовый файл **./adb logcat -d | findster todolist > d:/adb/todolost/todolost.txt**
7. Скопировать логи приложения todolist на компьютер.**./adb push** 
 8. Удалить приложение todolist с телефона через ADB **./adb uninstall com.android.todolist**
