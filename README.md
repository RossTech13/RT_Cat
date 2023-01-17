# RT_Cat
Работает на Node.js и discord.js
Версия 1.0.0
Автор: Ross_Tech
Дискорд сервер разработчика: https://discord.gg/E5BUGPVSn9

## Установка

Есть два пути установки данного бота, автоматизированный и ручной.

##Автоматизированный
1. Скачать Visual Studio Code.
2. Установивать плагины и расширения:
    Name: Node.js Extension Pack - https://marketplace.visualstudio.com/items?itemName=waderyan.nodejs-extension-pack
    Name: Node Extension Pack - https://marketplace.visualstudio.com/items?itemName=swellaby.node-pack
    Name: Discord.js docs - https://marketplace.visualstudio.com/items?itemName=gtjman.discord-js-docs
    Name: Discord Tools - https://marketplace.visualstudio.com/items?itemName=Darkempire78.discord-tools
    Name: Discord Presence - https://marketplace.visualstudio.com/items?itemName=icrawl.discord-vscode

##Ручной
1. Зайти на сайт [discordapp.com] и нажать на кнопку <kbd>New Application</kbd>
2. На сайте в настройках нужно создать бота и скопировать его TOKEN
3. Скопировть файлы из репозитория на свой локальный компьютер
4. Добавить TOKEN бота в файл **config.json**
5. Установить [Node.js&reg;] LTS без **node-gyp**
6. Выполнить команды от имени Администратора (для win10)
  ```
  mkdir %APPDATA%\nvm & cd %APPDATA%\nvm
  curl -OL https://github.com/coreybutler/nvm-windows/releases/latest/download/nvm-setup.zip
  tar -xf nvm-setup.zip && start /wait nvm-setup.exe
  --mkdir "%PROGRAMFILES%\nodejs" & copy /B %APPDATA%\nvm\settings.txt C:\
  ```
7. Про процессе установки подтвердить интеграцию [Node.js&reg;]

6. ~Затем открыть: Компьютер - Свойства - Дополнительные параметры системы - Переменные среды  
и заменить в **NVM_SYMLINK** на короткий путь `C:\Progra~1\nodejs`~


  ```
  --nvm install 16.9 && nvm use 16.9
  ```
  --Файл `settings.txt` скопируется в корень диска `C:\`



8. Выбрать через консоль каталог с файлами бота, и запустить `npm install discord.js` (или все модули `npm install` из **package.json**)
9. Запустить бота: **start_bot.bat**

[discordapp.com]: //discordapp.com/developers/
[Node.js&reg;]: //nodejs.org/dist/latest-v16.x/

### Примечание: установить зависимости

1. https://github.com/danielzzz/node-ping
2. ? `npm install moment-timezone`

## Links

* [Creating DiscordApp and obtaining Token](//anidiots.guide/getting-started/getting-started-long-version)
* [Презентация Node.js&reg;](//urfu-2016.github.io/javascript-slides/09-nodejs/)

## Licensing

RT_Cat_Bot is licensed under the [License].
