# Ultimate Media Knob

README on Eng - Coming Soon!

Макро клавиатура - с блэкджеком и шлюхами.
*В данный момент в статусе бета, возможны баги, WorkInProgress!

![PIC1](/img/log.png)  
3D-модель корпуса отсюда - [Thingiverse](https://www.thingiverse.com/thing:4343186).

### Функции
Основной функционал:
  - Регулировка громкости;
  - Выключение звука;
  - Пауза;
  - Переключение треков;
  - Несколько раскладок, 4 в данный момент;
  - Горячие клавиши в браузере;
  - Горячие клавиши на переключmarkение окон;
  - Запоминает последний использованный режим.


### Схема

![PIC0](/img/sch.jpg)
### Инструкция:
Энкодер имеет 5 вариантов управления:  
 - Поворот по часовой стрелке;
 - Поворот против часовой стрелки;
 - Нажатие;
 - Двойное нажатие;
 - Удержание.  
  
В коде происано 4 раскладки (режима), в каждой раскладке каждому действию назначена своя горячая клаиша.  
  
Раскладка 1:
- Поврот по часовой: Громкость +;
- Поврот против часовой: Громкость -;
- Нажатие: Пауза;
- Двойное нажатие: След. Трек;
- Удержание: Выкл. Звука;

### ToDo:

Если есть идеи как и чем дополнить устройство, пишите, открывайте Issue;

 - ~~Написать обработку двух тумблеров (MTS-102/ON-ON).
   Возможно перенесу на тактовую кнопку если ничего не придумаю.~~  
  Теперь раскладки переключаются по кругу нажатием тактовой кнопкой.  
 - Улучшить вывод на дисплей.  
 Начал рисовать вывод на дисплей.
 - Возможно добавлю вывод температуры ЦП или с датчика на экран.  
  Вывод температуры цп приоритетнее, но не уверен что смогу сделать.
 - WS2812, свой цвет у каждого режима, возможно с эффектом в духе "Knight Rider".  
 - В планах IR управление с пульта, чтобы лёжа на диване управлять воспроизведением.  
    
License
----

MIT

**Open Source**
