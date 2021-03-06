## External Storage

Общедоступное место для хранения файлов.

Находится на съёмном носителе или в публичном разделе внутренней памяти.

<br>

*Use case*:  
* Медиа-файлы
* Не критичные для работы приложения данные

------

## External Storage


* `getExternalFilesDir()`
* `getExternalCacheDir()`

<br>

Нужны разрешения:
<!-- .element: class="fragment" data-fragment-index="1" -->

<pre><code class="java large" data-trim data-noescape>
&lt;uses-permission
        android:name="android.permission.READ_EXTERNAL_STORAGE"/>
&lt;uses-permission
        android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
</code></pre>

<!-- .element: class="fragment" data-fragment-index="1" -->

<br>


>*Caution!*
>Файлы могут быть перезаписаны, удалены или недоступны!

<!-- .element: class="noveo-warn fragment" data-fragment-index="2" -->

<img style="float: right" src="lecture/storage/img/external_storage.png">

<br>