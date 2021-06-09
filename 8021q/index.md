802.1q

IEEE 802.1Q — открытый стандарт, который описывает процедуру тегирования трафика для передачи информации о принадлежности к VLAN по сетям стандарта IEEE 802.3 Ethernet.

 
TPID, идентификатор протокола тегирования
- TCI состоит из следующих полей:
- - PCP приоритета передаваемого трафика
- - DEI Индикатор допустимости удаления
- - VID какому VLAN принадлежит кадр


<img src="https://raw.githubusercontent.com/xxl601/xxl601.github.io/main/8021q/1.png">


 - Access Port – участники VLAN сетей 
 - Trunk Port – проводники между VLAN сетями
 - CAM table – таблица кто куда.


 - Позволяет разделить одну физическую сеть на несколько логических (независимых)
 - Безопасность
 - Распределение нагрузки
 - Ограничение широковещательного трафика
 - Трафик бегает только по логической сети

<img src="https://raw.githubusercontent.com/xxl601/xxl601.github.io/main/8021q/2.png">

<img src="https://raw.githubusercontent.com/xxl601/xxl601.github.io/main/8021q/3.png">

<img src="https://raw.githubusercontent.com/xxl601/xxl601.github.io/main/8021q/4.png">
