# FrequencyMeter_IotManager
Frequency Meter, Percent Flicker, Flicker Index for IotManager by reading from Analog pin.

When use Photoresitor GL5516 use voltage divider Resistense 1000 Om for maximum range of ilumination or 10kOm for more senetivity (for low light)

![freqMeter](https://user-images.githubusercontent.com/4175310/196288090-e0927166-1d5a-453d-aeca-f00d5c734c5b.png)

Photo Resistor Module uses 10KOm resistense. Do connect it as shown on the picture (not like shown on the module): 


![PhotoResiatorModule](https://user-images.githubusercontent.com/4175310/204156110-1ed5c3fe-cb17-4d95-9289-fc3cdaaf9ca4.png)

At Configuration select all Elements with Frequensy Meter. It shold look like this. 


![Configuration](https://user-images.githubusercontent.com/4175310/204156672-79961f19-63dd-49f4-a33c-3d0c2571e63f.png)



No need to change any paramenters for Esp8266. For Esp32 - set pin only.



This you will see at IotManager

![FreqMeterWebView](https://user-images.githubusercontent.com/4175310/196288916-9a79bb97-90c4-4f06-8625-4ccf2a6485a5.png)

Измеритель частоты, Процент пульсации, Индес пульсации для прошивки IotManager для Esp8266/Esp32 через аналоговый пин.

Подробнее о параметрах - 
https://www.uprtek.com/ru/faq/knowledge-qa/what-is-flicker-metrics-percent-flicker-flicker-index-svm

Если используйте фоторезеистор GL5516 то берите для делителя напряжения сопротивление 1000 Ом для максимального диапазна освещенности или 10кОм для большей чуствительности (при тусклом освещении)

В модуле Фото-резистора используется 10кОм. Подключайте его как показано на картинке (а не как указано на модуле).
Питание 3.3В в любом случае.


