# crypto 
Программы для кодирования одних данных в другие 
![logo](/logo.bmp)
+ Для запуска исходников нужно [скачать Processing](https://processing.org/download/)
+ Установить пакет [Java](https://java.com/ru/download/)
+ В самой программе Processing установить библиотеку **ControlP5**: зайти "Набросок / Импортировать библиотеку... / Добавить библиотеку...", в поиске найти и установить библиотеку ControlP5. Требуется подключение к интернету!
+ Для примеров со звуком установить библиотеку **Sound**
+ В папках с исходниками есть папка **bin**, там лежит скомпилированная прогамма для win32 и win64
+ Для запуска исходника открываем файл *.pde* при помощи Processing

## Папка image-text
### Кодирование текста в изображение
+ **crypto** - вариант с двумя картинками (старый). Во вкладке *old* лежит несколько алгоритмов
+ **cryptoText** - вариант с ключом шифрования и случайным распределением пикселей
+ **colorTest** - программа для тестирования смеси цветов из видео

## Папка image-sound
### Кодирование звука изображение и наоборот
+ **cryptoAmpli** - пакует изображение в звук
+ **cryptoProSound** - пакует звук в изображение
+ **cryptoSpectrum** - зашивает картинку в спектр звука
