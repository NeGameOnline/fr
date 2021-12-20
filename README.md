# WTF?
Скрипт разворачивает немного переделланый проект ivadim/fruitnanny без doker. Работает только на Raspberry Pi OS **BUSTER**.

# Install git and run sh
```
wget https://raw.githubusercontent.com/NeGameOnline/fr/main/fr.sh
sudo chmod +x fr.sh
./fr.sh
```

# Главная страница index.ejs
Edit  /opt/fruitnanny/views/index.ejs

# FAQ vcgencmd commands for raspberrypi
vcgencmd measure_temp - получение температуры процессора \
vcgencmd get_camera - показать подключена или нет официальная CSI-камераivadim/fruitnanny
vcgencmd mem_oom - Статистика событий Out Of Memory, случившихся в области памяти VC4 \
vcgencmd get_throttled - показывает причины снижения производительности процессора. Для расшифровки нужно перевести вывод команды в двоичный формат и смотреть установленные биты (нумерация справа налево)
- Бит 0 В настоящий момент производительность процессора снижена из-за проблем с питанием, низкое напряжение
- Бит 1 В настоящий момент производительность процессора снижена из-за ручного ограничения частоты
- Бит 2 В настоящий момент производительность процессора снижена
- Бит 3 В настоящий момент производительность процессора снижена из-за перегрева процессора
- Бит 16 Производительность процессора в этом сеансе работы была когда-то снижена из-за проблем с питанием, низкое напряжение
- Бит 17 Производительность процессора в этом сеансе работы была когда-то снижена&amp;amp;amp;amp;amp;amp;amp;nbsp;из-за ручного ограничения частоты
- Бит 18 Производительность процессора в этом сеансе работы была когда-то снижена
- Бит 19 Производительность процессора в этом сеансе работы была когда-то снижена из-за перегрева процессора

