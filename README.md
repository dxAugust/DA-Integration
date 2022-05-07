# 🧡 DA-Integration
![alt-текст](https://i.imgur.com/PZIsLTG.png "MMM баннер")

#### Простой плагин для сервера на ядре [Tshock](https://github.com/Pryaxis/TShock) который принимает события в реальном времени с сервиса приёма пожертвований [DonationAlerts](https://www.donationalerts.com/). Данный плагин взаимодействует с сервером [Centifugo](https://centrifugal.github.io/centrifugo/) от [DonationAlerts](https://www.donationalerts.com/) в реальном времени.

# 🛠 Используемые библиотеки 
* websocket-sharp
* Newtonsoft.Json

# 🌳 Пример работы 
![alt-текст](https://i.imgur.com/6yuSXeT.gif "Пример вывода доната в чат")


# 💾 Для работы плагина
* Требуется установить **Visual Studio**
* Создать проект "Библиотека классов C#"
* Затем копировать весь исходный код скачанный с Github в папку созданного проекта
* Подключить библиотеку **websocket-sharp (Из папки libs)**
* В классе **Config.cs** поменять: **client_id, client_secret, redirect_URL, authCode** на свой
* Собрать плагин
* Собранный файл плагина и библиотеку переместить в папку **ServerPlugins** в директории сервера

# ☕ Поддержка
[Спасибки, если заглянешь ко мне на стрим :)](https://www.youtube.com/channel/UCgWZ8m2ag5WpMT76HE7Kw5w)