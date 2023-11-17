# Инструкция по установке OpenServer

**OpenServer** - это портативная программная среда, созданная специально для веб-разработчиков с учётом их рекомендаций и пожеланий.

## Скачивание установщика OpenServer (946мб)

* [Официальный сайт OpenServer](https://ospanel.io/download/) (~ 4 часа безудержного веселья)

* [Диск Mail.ru](https://cloud.mail.ru/public/e6oo/ZHB1mtuNf)

* [Диск Google](https://drive.google.com/file/d/1ZHdC6FttbPiGWgIF9v0ljIaKgYzDl85x/view?usp=sharing)

* [Диск Яндекс](https://disk.yandex.ru/d/1I1uOonHOKOdcQ)

## Установка OpenServer
> После установки OpenServer будет занимать около 6-7гб

* После скачивания запустите <u>**OpenServer.exe**</u>
![](/IMG/1.png)
*Приветственное окно установщика*

* В следующей вкладке нужно принять лицензионное соглашение
![](/IMG/2.png)  
*Кто-то его читает?*

* В следующей вкладке дополнительная информация от разработчика, по поводу установки
![](/IMG/3.png)  
*Разработчик рекомендует устанавливать OpenServer на SSD*

* Выбор пути установки
![](/IMG/4.png)

* В следующей вкладке нужно выбрать из выпадаюищего списка "***Компактная установка***" 
![](/IMG/5.png)

>Уберите галочки с Apache версий, в которых есть **PHP пятой версии**
![](/IMG/6.png)  
*Apache - HTTP веб сервер*

>Уберите галочки с PHP версий: **5.2, 5.3, 5.4, 5.5, 5.6**  
![](/IMG/7.png)  
*PHP 5 версии "умер" ещё в 2018 году*  
***Все другие компоненты оставляем без изменений***

* Создание ярлыков в меню пуск (на ваш выбор)
![](/IMG/8.png)

* Дополнительные задачи оставляем без изменений
![](/IMG/9.png)

* Нажимаем ***Установить*** и ждём конца установки
![](/IMG/10.png)

>После того, как OpenServer установился, перезагружаем ПК

# Настройка модулей OpenServer
Изначально в OpenServer отключены и не установлены актульные модули, поэтому далее по инструкции их надо включить и установить в настройках OpenServer

* Запустите OpenServer и вас попросят выбрать язык программы, выберете русский язык. Затем в панеле задачи или в трее появится красный флажок  
![](/IMG/11.png)  
Нажмите на него правой кнопкой мыши и появится меню управления OpenServer  
![](/IMG/12.png) 

* Нажимаем на ***Настройки***  
Откроется окно с настройками OpenServer, нас интересует вкладка ***Модули***
![](/IMG/13.png)  
1. В пункте **HTTP** выберете _Apache_2.4-PHP_8.0-8.1_  
2. В пункте **PHP** выберете _самую последнюю версию_  
3. В пункте **MySQL / MariaDB** выберете _MariaDB-10.8-Win10_  
![](/IMG/14.png)

**Остальные пункты не трогайте, после того, как выберете все модули, обязательно сохраните настройки!**