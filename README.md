# vpngate-client
<div align="center">

# 🌐 VPNGate Client

**A lightweight, free Windows VPN client for the public VPN Gate network.**
No OpenVPN. No SoftEther Client. Just run it and connect.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%7C%2011-blue)
![Languages](https://img.shields.io/badge/languages-EN%20%7C%20RU%20%7C%20TK-green)
![Theme](https://img.shields.io/badge/theme-light%20%7C%20dark-lightgrey)


</div>

---

## ✨ What is it?

**VPNGate Client** is a standalone desktop app that connects you to free volunteer-run servers from the official [VPN Gate](https://www.vpngate.net) project.

It has its own built-in protocol client and uses the **Wintun** virtual adapter. One program, one window, one button.

## 🚀 Features

- 🔘 **One-click connect**: big power button, live status and speed.
- 🤖 **Auto mode**: tries servers that work on your network and stays on the first healthy one.
- 📋 **Server list from VPN Gate**: grouped by country, with ping for every server.
- 🧭 **Two tunnel modes**
  - **All traffic**: everything goes through the VPN.
  - **Selected apps only**: only the programs you pick use the VPN; you can also exclude apps so they bypass it.
- ⚡ **UDP or TCP transport**: switch protocols if your network blocks one of them.
- 🛠 **Fine tuning**: custom DNS, automatic or manual MTU.
- ➕ **Add your own servers**: paste a VPN Gate CSV or a list of IPs, or import a file.
- 📤 **Export** the server list, 🔄 **refresh pings**, ⬇️ **download** a fresh list, 🗑 **clear** the list.
- 📜 **Built-in log panel** for troubleshooting.
- 🌗 **Light and dark themes**, 🌍 **English, Russian and Turkmen** interface.
- 🔔 **Tray icon**, single instance, remembers your settings.

## 📥 Installation

1. Download `[VPNGate-Client.exe / VPNGate-Client.zip]` from the **Assets** section below.
2. If you downloaded a zip, extract it to any folder.
3. Run the program **as administrator** (right-click → *Run as administrator*). Creating a virtual network adapter requires it.

> No installer, no dependencies. To uninstall, just delete the folder.

## 🧑‍💻 How to use

1. **Launch** the app. On the first start, pick your language and theme.
2. **Pull up the server list** with the "Servers" panel (drag the handle at the bottom up, or click it). If it is empty, press the ⬇️ **download** icon.
3. **Choose a server** or leave **Auto** selected.
4. Press the big **power button** to connect. Press it again to disconnect.

### Toolbar icons

| Icon | What it does |
|:---:|---|
| ➕ | Add servers: paste a list or import a CSV/TXT file |
| 🔀 | Tunneling: choose *all traffic* or *selected apps* |
| 📄 | Logs |
| ⚙️ | Settings |

### Servers panel icons

| Icon | What it does |
|:---:|---|
| 🔄 | Refresh server ping |
| ⬇️ | Download the server list |
| ⬆️ | Export servers to a file |
| 🗑 | Delete all servers |

### Tunnel mode: selected apps

1. Click the **tunnel icon** to open *Settings → Tunnel*.
2. Switch to **Selected apps**.
3. Add the programs (`.exe`) or process names (e.g. `chrome.exe`) that should use the VPN.
4. Connect. Only those apps will go through the VPN, the rest of your system stays on the normal connection.

## 🩺 Troubleshooting

- **Cannot connect / slow connection?** Try another server, or switch transport between **UDP** and **TCP** in *Settings*.
- **Pages hang or load partially?** Set MTU to `1300` or `1200` in *Settings → MTU*.
- **Nothing happens on launch?** Make sure the app is running as administrator and check the log panel.
- **Antivirus warning?** The app is packaged with PyInstaller and creates a network adapter, which some antivirus programs flag by mistake (false positive). You can check the file on [VirusTotal](https://www.virustotal.com).

## ⚠️ Disclaimer

VPN Gate servers are run by **volunteers**. Do not send passwords, banking data or anything sensitive through servers you do not trust, and use the VPN in accordance with the laws of your country. This is a hobby project provided **"as is"**, without any warranty.

## 🙏 Credits

- [VPN Gate Academic Experiment Project](https://www.vpngate.net), University of Tsukuba, for the public server network.
- [SoftEther VPN](https://www.softether.org) protocol.
- [Wintun](https://www.wintun.net) virtual network adapter by WireGuard.

---

<details>
<summary><h2>🇷🇺</summary>

## ✨ Что это?

**VPNGate Client** это отдельная программа для компьютера, которая подключает вас к бесплатным серверам добровольцев из официального проекта [VPN Gate](https://www.vpngate.net).

В неё встроен собственный клиент протокола SoftEther, а работает она через виртуальный адаптер **Wintun**. Поэтому ставить OpenVPN или SoftEther VPN Client **не нужно**. Одна программа, одно окно, одна кнопка.

## 🚀 Возможности

- 🔘 **Подключение в один клик**: большая кнопка питания, статус и скорость в реальном времени.
- 🤖 **Режим Auto**: пробует серверы, которые работают в вашей сети, и остаётся на первом рабочем.
- 📋 **Список серверов VPN Gate**: сгруппирован по странам, у каждого сервера виден пинг.
- 🧭 **Два режима туннеля**
  - **Весь трафик**: всё идёт через VPN.
  - **Выбранные приложения**: через VPN работают только программы, которые вы укажете. Можно также исключить приложения, чтобы они шли мимо VPN.
- ⚡ **Транспорт UDP или TCP**: переключайтесь, если ваша сеть блокирует один из них.
- 🛠 **Тонкая настройка**: свой DNS, автоматический или ручной MTU.
- ➕ **Свои серверы**: вставьте CSV из VPN Gate или список IP-адресов, либо импортируйте файл.
- 📤 **Экспорт** списка серверов, 🔄 **обновление пинга**, ⬇️ **скачивание** свежего списка, 🗑 **очистка** списка.
- 📜 **Встроенная панель логов** для поиска проблем.
- 🌗 **Светлая и тёмная темы**, 🌍 интерфейс на **английском, русском и туркменском**.
- 🔔 **Значок в трее**, запуск только одной копии, программа помнит ваши настройки.

## 📥 Установка

1. Скачайте `[VPNGate-Client.exe / VPNGate-Client.zip]` в разделе **Assets** ниже.
2. Если скачали zip, распакуйте его в любую папку.
3. Запустите программу **от имени администратора** (правой кнопкой мыши → *Запуск от имени администратора*). Для создания виртуального сетевого адаптера это необходимо.

> Установщик не нужен, зависимости тоже. Чтобы удалить программу, просто удалите папку.

## 🧑‍💻 Как пользоваться

1. **Запустите** программу. При первом запуске выберите язык и тему.
2. **Откройте список серверов**: потяните панель «Серверы» снизу вверх или нажмите на неё. Если список пуст, нажмите значок ⬇️ **скачать**.
3. **Выберите сервер** или оставьте **Auto**.
4. Нажмите большую **кнопку питания**, чтобы подключиться. Нажмите ещё раз, чтобы отключиться.

### Значки в верхней панели

| Значок | Что делает |
|:---:|---|
| ➕ | Добавить серверы: вставить список или импортировать CSV/TXT |
| 🔀 | Туннелирование: *весь трафик* или *выбранные приложения* |
| 📄 | Журнал |
| ⚙️ | Настройки |

### Значки в панели «Серверы»

| Значок | Что делает |
|:---:|---|
| 🔄 | Обновить пинг серверов |
| ⬇️ | Скачать список серверов |
| ⬆️ | Экспортировать серверы в файл |
| 🗑 | Удалить все серверы |

### Режим туннеля: выбранные приложения

1. Нажмите **значок туннеля**, откроются *Настройки → Туннель*.
2. Переключитесь на **Выбранные приложения**.
3. Добавьте программы (`.exe`) или имена процессов (например, `chrome.exe`), которые должны работать через VPN.
4. Подключитесь. Через VPN пойдут только эти приложения, остальная система останется на обычном соединении.

## 🩺 Если что-то не работает

- **Не подключается или медленно?** Попробуйте другой сервер или переключите транспорт между **UDP** и **TCP** в *Настройках*.
- **Страницы зависают или грузятся не полностью?** Поставьте MTU `1300` или `1200` в *Настройки → MTU*.
- **При запуске ничего не происходит?** Убедитесь, что программа запущена от имени администратора, и загляните в журнал.
- **Антивирус ругается?** Программа собрана через PyInstaller и создаёт сетевой адаптер, из-за чего некоторые антивирусы срабатывают ошибочно (ложное срабатывание). Файл можно проверить на [VirusTotal](https://www.virustotal.com).

## ⚠️ Отказ от ответственности

Серверы VPN Gate содержат **добровольцы**. Не передавайте пароли, банковские данные и другую важную информацию через серверы, которым не доверяете, и пользуйтесь VPN в соответствии с законами вашей страны. Это любительский проект, который распространяется **«как есть»**, без каких-либо гарантий.


</details>

---

<div align="center">

⭐ If you like the project, leave a star! / Если проект понравился, поставьте звезду!

</div>
