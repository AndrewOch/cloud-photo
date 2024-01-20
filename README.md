# cloudphoto
 
## Сборка

* Для сборки приложения потребуется утилита PyInstaller
```
pip install pyinstaller
```
* Откройте Терминал и перейдите в директорию репозитория
```
cd <path/to/cloudphoto>
```
* Выполните следующую команду:
```
pyinstaller --onefile cloudphoto.py
```
* Исполняемый файл создастся в директории "./dist", вы можете запускать скрипт оттуда:
```
./dist/cloudphoto init
```
* Вы также можете добавить исполняемый файл в PATH, чтобы запускать его в любом месте системы. Для этого переместите файл в usr/local/bin
```
mv ./dist/cloudphoto /usr/local/bin/cloudphoto
```
