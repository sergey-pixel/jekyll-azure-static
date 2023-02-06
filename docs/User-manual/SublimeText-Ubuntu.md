---
layout: default
title: Установка Sublime Text на ПК с ОС Ubuntu
parent: Руководства пользователя
nav_order: 1
---

# Установка Sublime Text на ПК с ОС Ubuntu
{: .no_toc }
С помощью инструкции вы сможете установить текстовый редактор Sublime Text 4 на ПК с операционной системой  Ubuntu 20.04 и выше, а также настроить ассоциацию расширений HTML-файлов с данной программой.

Варианты установки Sublime Text:
* TOC
{:toc}
### Установка с помощью &laquo;Центра Приложений&raquo; (Ubuntu Software)

1. Нажмите значок &laquo;Показать приложения&raquo;. По умолчанию он находится внизу на левой боковой панели.
   ![Показать приложения](https://digit-dev.net/Images/Printscreen13.jpg)
2. Введите в строке поиска &laquo;Ubuntu&raquo;, а затем нажмите значок &laquo;Центра Приложений&raquo; (Ubuntu Software).
   ![Центр приложений](https://digit-dev.net/Images/Printscreen2-1.jpg)
3. Нажмите в верхнем меню &laquo;Центра Приложений&raquo; иконку <img  style="display: inline; vertical-align: bottom;" src="https://digit-dev.net/Images/Printscreen19-1.jpg">.
4. Наберите &laquo;Sublime Text&raquo; в строке поиска.
   ![Поиск приложения](https://digit-dev.net/Images/Printscreen20.jpg)
5. Выберите приложение &laquo;sublime-text&raquo;.
   ![Панель с приложения](https://digit-dev.net/Images/Printscreen21.jpg){: style="margin-top: 10px"}
6. Нажмите кнопку &laquo;Установить&raquo;, введите пароль для учетной записи с правами администратора.
   ![Установка приложения](https://digit-dev.net/Images/Printscreen22.jpg)
7. Дождитесь установки приложения. 
8. Зайдите в &laquo;Центр Приложений&raquo;. Вы увидите Sublime Text в списке установленных программ. 

### Установка из репозитория разработчика

**Важно**. Для выполнения всех команд требуются права администратора.
1. Чтобы запустить терминал, нажмите Ctrl+Alt+Del.
2. Установите GPT-ключ: 
  `wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | gpg --dearmor | sudo tee /etc/apt/trusted.gpg.d/sublimehq-archive.gpg > /dev/null` 
3. Добавьте ссылку на репозиторий в каталог etc/apt/source.list.d:
  `echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list`
4. Обновите списки репозитория:
  `sudo apt update`
5. Установите приложение:
  `sudo apt install sublime-text`
6. Программа готова к работе.

Вы можете запустить Sublime Text из &laquo;Цента Приложений&raquo; (Ubuntu Software) или, введя ее название в строке поиска. 


### Настройка ассоциации HTML-файлов с Sublime Text
{: .no_toc }
1. В контекстном меню любого HTML-файла выберите &laquo;Свойства&raquo;.
   ![Файл](https://digit-dev.net/Images/Printscreen24.jpg){: style="margin-top: 10px"}
2. Перейдите на вкладку &laquo;Открыть с помощью&raquo;.
   ![Открыть с помощью](https://digit-dev.net/Images/Printscreen18.jpg){: style="margin-top: 10px"}
3. Выберите Sublime Text.
4. Нажмите &laquo;Установить по умолчанию&raquo;.  
