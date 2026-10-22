# Компьютерные сети

Учебный репозиторий. У каждого занятия есть `class` с конспектом и `homework` с описанием работы. Скриншоты лежат в `homework/screenshots`.

Каталог `theory/` хранит презентации, по которым собраны конспекты. В `homework/` оставлены исходные текстовые работы. Скриншоты из датированных папок перенесены к урокам.

## Занятия

| Урок | Конспект | Домашняя работа | Дата |
| --- | --- | --- | --- |
| 1 | [Введение](<lesson_01/class/Введение в компьютерные сети.md>) | [Нет сдачи](lesson_01/homework/README.md) | — |
| 2 | [OSI и TCP/IP](<lesson_02/class/Модели OSI и TCP-IP.md>) | [Пять примеров по уровням](lesson_02/homework/README.md) | 14.09 |
| 3 | [Физический уровень](<lesson_03/class/Физический уровень.md>) | [Нет сдачи](lesson_03/homework/README.md) | — |
| 4 | [MAC-адреса](<lesson_04/class/MAC-адреса.md>) | [Дубли MAC и схема](lesson_04/homework/README.md) | 16.09 |
| 5 | [IPv4](<lesson_05/class/Адресация IPv4.md>) | [Расчёт подсетей](lesson_05/homework/README.md) | 21.09 |
| 6 | [Коммутаторы и хабы](<lesson_06/class/Коммутаторы хабы и проверка связи.md>) | [Схема, ping, симуляция](lesson_06/homework/README.md) | 23.09 |
| 7 | [Деление на подсети](<lesson_07/class/Разделение сети на подсети.md>) | [Нет сдачи](lesson_07/homework/README.md) | — |
| 8 | [Расчёт подсетей](<lesson_08/class/Расчёт подсетей.md>) | [Две сети /24](lesson_08/homework/README.md) | 28.09 |
| 9 | [Маршрутизация](<lesson_09/class/Маршрутизация.md>) | [Три схемы](lesson_09/homework/README.md) | 30.09 |
| 10 | [DHCP](<lesson_10/class/Протокол DHCP.md>) | [Схема и конспект DHCP](lesson_10/homework/README.md) | 5.10 и 7.10 |
| 11 | [Маршрутизация в Cisco](<lesson_11/class/Маршрутизация в Cisco.md>) | [Нет сдачи](lesson_11/homework/README.md) | — |
| 12 | [NAT](<lesson_12/class/Технология NAT.md>) | [Нет сдачи](lesson_12/homework/README.md) | — |
| 13 | [NAT в Cisco](<lesson_13/class/NAT в Cisco.md>) | [Веб-сервер](lesson_13/homework/README.md) | 12.10 |
| 14 | [TCP и UDP](<lesson_14/class/Транспортный уровень TCP и UDP.md>) | [Выжимка](lesson_14/homework/README.md) | 14.10 |
| 15 | [DNS](<lesson_15/class/Система DNS.md>) | [Имя www.test.com](lesson_15/homework/README.md) | 14.10 |
| 16 | [Wireshark](<lesson_16/class/Анализ трафика Wireshark.md>) | [Три захвата](lesson_16/homework/README.md) | 19.10 |

## Как устроен репозиторий

Занятия лежат в папках `lesson_01`–`lesson_16`. У каждого урока один и тот же набор:

- `class/` — конспект занятия, один файл Markdown;
- `homework/README.md` — что сдано по этому уроку: условие, решение и, если конспект собран по этой работе, ссылка на файл в `class/`;
- `homework/screenshots/` — скриншоты этой сдачи. Если снимков не было, папка держится файлом `.gitkeep`. Сам `.gitkeep` работой не считается.

Темы и даты стоят в таблице выше. Отдельной датированной сдачи нет у уроков 1, 3, 7, 11 и 12: в их `homework/README.md` это записано.

`theory/` хранит презентации, по которым собраны конспекты. Копии в папки уроков не клались:

- `Модели.pptx`
- `Ipv4 (3).pptx`
- `маршрут.ppt`
- `маршрут циско.ppt`
- `DHCP короткий (2).pptx`
- `nat теор.pptx`
- `nat в cisco.pptx`
- `DNS (1).pptx`

`homework/` — исходные папки по датам. Текстовые файлы остались в них. Скриншоты перенесены в `lesson_XX/homework/screenshots` и названы по теме. Папка, из которой ушли только снимки, оставлена с `.gitkeep`.

| Исходная папка | Что в ней осталось | Куда перенесено |
| --- | --- | --- |
| `homework/homework 14.09` | `hw-14-09.md` | урок 2, скриншотов не было |
| `homework/homework 16.09` | `hw-16-09.md` | урок 4, `network-scheme.png` |
| `homework/homework 21.09` | `hw-21.09.md` | урок 5, скриншотов не было |
| `homework/homework 23.09` | `.gitkeep` | урок 6: `network.png`, `ping.png`, `simulation.png` |
| `homework/homework 28.09` | `hw-28.09.md` | урок 8, скриншотов не было |
| `homework/homework 30.09` | `.gitkeep` | урок 9: `routers-and-switch.png`, `routers-and-hubs.png`, `router-triangle.png` |
| `homework/homework 5.10` | `.gitkeep` | урок 10: `routing-topology.png` |
| `homework/homework 7.10` | `dhcp.md` | урок 10, скриншотов не было |
| `homework/homework 12.10` | `.gitkeep` | урок 13: `nat-web-server.png` |
| `homework/homework14.10` | `tcp_udp.md` | урок 14, скриншотов не было |
| `homework/homework14.10(2)` | `.gitkeep` | урок 15: `dns-ping.png` |
| `homework/homework 19.10` | `.gitkeep` | урок 16: `tcp-psh-ack.png`, `tcp-ack.png`, `udp-quic.png` |

Проверочные файлы лежат отдельно от занятий:

- `control-test/Samostoyatelnaya.md` — самостоятельная работа;
- `exam/exam.docx` — экзамен.
