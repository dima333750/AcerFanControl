Это форк проекта https://github.com/jaryn-kubik/AcerFanControl, Большая благодарность jaryn-kubik !!
Добавлена поддержка новым материнских плат, протестировано на ACER Aspire A315-42

## Важно - если вы получите ошибку «неверная ручка устройства» после любого большего обновления Windows, попробуйте переустановить драйверы

### Что оно делает
- Мониторирует температуру процессора/графического процессора и включает вентилятор до максимальной скорости при достижении установленной температуры.
- Протестировано на ACER Aspire A315-42, Acer Aspire V3-571G, должен работать на 5750G.

### Применение
1. [Установите драйверы, предоставленные Acer](https://raw.githubusercontent.com/dima333750/acerfancontrol/master/drivers.zip) (запустить common.exe) и перезагрузить компьютер.
2. [Загрузите последний выпуск](https://github.com/dima333750/AcerFanControl/releases)
3. Распакуйте его где-нибудь и запустите.
- Переключатель контролирует температуру, при которой он поворачивает вентилятор на максимум
- Другой контролирует время после того, как кулер отключится.
- ВКЛ/ВЫКЛ для ручного включения скорость на максимум

[Второй драйвер если первый не работает](https://github.com/dima333750/AcerFanControl/blob/master/driver2.zip) (запустить common.exe) и перезагрузить компьютер.

### Кредиты
- https://github.com/neduard/acer_5750G_fan_maximiser
- http://community.acer.com/t5/Notebooks-Netbooks/Fan-Control-Problems-With-5750G-And-similar-machines/m-p/199637/highlight/true#M33756.
- http://openhardwaremonitor.org/

Оригинальное описание.

## IMPORTANT - if you get an error "Invalid device handle" after any bigger Windows update, try reinstalling the drivers

### What it does
- Monitors the CPU/GPU temperature and turns the fan to maximum speed when the set temperature is reached.
- Tested on acer aspire V3-571g, should work on 5750g.

### Usage
1. [Install the drivers provided by Acer](https://raw.githubusercontent.com/jaryn-kubik/AcerFanControl/master/drivers.zip) (run common.exe)
2. [Download the latest release](https://github.com/jaryn-kubik/AcerFanControl/releases/latest)
3. Unzip it somewhere and start it up.
- one slide controls the temperature at which it turns the fan to the max
- other one controls the time after it will tone the fan back down.
- on/off is for manually setting the speed to max

### Credits
- https://github.com/neduard/acer_5750G_fan_maximiser
- http://community.acer.com/t5/Notebooks-Netbooks/Fan-Control-Problems-With-5750G-And-similar-machines/m-p/199637/highlight/true#M33756.
- http://openhardwaremonitor.org/
