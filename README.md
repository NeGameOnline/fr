# Install git and run sh

Без doker
```
wget https://raw.githubusercontent.com/NeGameOnline/fr/main/fr.sh
sudo chmod +x fr.sh
./fr.sh
```

С doker вариант 1

```
wget https://raw.githubusercontent.com/NeGameOnline/fr/main/fr_doker1.sh
sudo chmod +x fr_doker1.sh
./fr_doker1.sh
```

С doker вариант 2

```
wget https://raw.githubusercontent.com/NeGameOnline/fr/main/fr_doker2.sh
sudo chmod +x fr_doker2.sh
./fr_doker2.sh
```

# index.ejs

Download index.ejs and replace /opt/fruitnanny/views/index.ejs
```
cd ~
wget https://raw.githubusercontent.com/NeGameOnline/fr/main/index.ejs
sudo mv index.ejs /opt/fruitnanny/views/
```


# vcgencmd commands for raspberrypi
vcgencmd measure_temp - получение температуры процессора \
vcgencmd get_camera - показать подключена или нет официальная CSI-камера \
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

