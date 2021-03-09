САМЫЕ РАСПРОСТРАНЕННЫЕ КОМАНДЫ ADB
Команда	Содержание
adb	Вывод всех команд в окно консоли
adb devices	Вывод на дисплей данных об устройствах, которые подключены к ПК, а также их серии
adb reboot	Перезагрузка Android
adb logcat	Сбор логов и их просмотр с телефона. Логи отображаются в командной строке
adb push C:\Users\user\Documents\temp.txt /sdcard	Позволяет отправлять документы с компьютера на мобильное устройство. Для этого требуется написать адрес к отправляемому файлу и место, где оно будет храниться на телефоне
adb logcat -d > ~/test.log	Сбор логов с телефона и их запись в отдельный файловый документ
adb shell screenrecord /sdcard/test.mp4	Запись дисплея телефона, с указанием места хранения файла, наименования и расширения
adb install C:\test.apk	Установка программы на устройство. Для этого нужно ввести путь к утилите
adb shell screencap /sdcard/test.png	Скриншот с мобильного устройства, с указанием места хранения, наименования и расширения




adb pull /storage/emulated/0/Download/app-deg.apk ../adb   --> cope from device to pc  adb pull PathOfFile0nDevice pathonpc


adb shell screencap /sdcard/screen.png   -> make screen on device

adb pull /sdcard/screen.png  Pathfile --> copy screen from device to folder pc