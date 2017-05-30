## Debug

<br>

#### Доступ к БД через `adb shell`

`$ adb exec-out run-as com.example.app cp /data/data/com.example.app/databases/your_database.db /sdcard/`

<br>

`$ adb pull /sdcard/your_database.db`


------

## Debug

<br>

#### Доступ к БД через [Device File Explorer](https://developer.android.com/studio/debug/device-file-explorer.html)

**View > Tool Windows > Device File Explorer**

Доступен в Android Studio 3.+

<img src="lecture/database/img/android_studio_3.0.png">
