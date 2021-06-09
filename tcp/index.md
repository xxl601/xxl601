"СНАЙПЕР"

Transmission Control Protocol (TCP, протокол управления передачей)

- Протокол транспортного уровня. Предназначен для передачи данных в сети. 
- Прежде чем начать передавать данные он устанавливает соединение с другим устройством (просто такой тип “Go?”, “Go!”), 
- после того как отправляющая сторона скинула, она ждет ответ что все ОК и если это так, то продолжает пересылку, цикл повторяется.
- Благодаря этому информация всегда передается в ПРАВИЛЬНОМ ПОРЯДКЕ.
- МЕНЬШЕ скорость передачи. БОЛЬШЕ надежность.

---

Transmission Control Protocol (TCP, протокол управления передачей) — один из основных протоколов передачи данных интернета. Предназначен для управления передачей данных интернета. Пакеты в TCP называются сегментами. В стеке протоколов TCP/IP выполняет функции транспортного уровня модели OSI.


<img src="https://raw.githubusercontent.com/xxl601/xxl601.github.io/main/tcp/1.png">


Длина заголовка (Data offset) занимает 4 бита и указывает значение длины заголовка, измеренное в 32-битовых словах. Минимальный размер составляет 20 байт (пять 32-битовых слов), а максимальный — 60 байт (пятнадцать 32-битовых слов). Длина заголовка определяет смещение полезных данных относительно начала сегмента. Например, Data offset равное 1111 говорит о том, что заголовок занимает пятнадцать 32-битных слова (15 строк*32 бита в каждой строке/8 бит = 60 байт).