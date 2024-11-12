Скачиваем скрипт командой:

wget https://raw.githubusercontent.com/Ravil86/setup-ipsec-vpn/refs/heads/master/vpnsetup.sh

wget https://git.io/vpnsetup -O vpnsetup.sh

4) После завершения, открываем vpnsetup.sh для редактирования:

sudo nano -w vpnsetup.sh

В котором в одинарных кавычках указываем свои значения:
YOUR_IPSEC_PSK=' Защищенный PSK IPsec должен состоять мин из 20 случайных символов.'
YOUR_USERNAME=' Ваш логин для VPN'
YOUR_PASSWORD=' Ваш пароль для VPN'
Создаём свой VPN-сервер IPsec / L2TP за пару минут на бесплатном VPS сервере от Oracle с ОС Ubuntu 20.04 (автоматизированная настройка) Умный дом, Ubuntu, Linux, VPS, Oracle, Виртуальная машина, VPN, Home Assistant, Длиннопост
5) Сохраняем и закрываем файл, нажав CTRL + X, Y, а затем ENTER.

6) Запускаем скрипт и идём на пару минут пить кофе ))

sudo sh vpnsetup.sh
