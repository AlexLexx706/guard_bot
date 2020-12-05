# Этап 1.1

После первых испытаний с пультом [китайского аналога PS2](https://aliexpress.ru/item/32857305986.html?spm=a2g0s.9042311.0.0.264d33edewPG74&_ga=2.150436022.1072583910.1607177262-750059769.1578514621&sku_id=65286515313):  

![](.gitbook/assets/photo5359604562882834894.jpg)

стало ясно, что эта штука **плохо обеспечивает** стабильную связь. Было принято решение реализовать свой собственный [пульт управления и базе модуля NRF24L01](https://app.gitbook.com/@alexlexx1/s/guard_bot/pult-upravleniya) и ответной части приёмника в роботе:  

![](.gitbook/assets/photo5359604562882834893.jpg)

Так же за одно с новой связью захотелось попробовать [ADNS-3080](https://www.openimpulse.com/blog/wp-content/uploads/wpsc/downloadables/ADNS-3080.pdf):  

![](.gitbook/assets/photo5359604562882834892.jpg)

Пример работы с данным сенсором был взят [тут](https://github.com/Lauszus/ADNS3080/blob/master/ADNS3080.ino)

### Принципиальная схема устройства:



Репозиторий с последней прошивкой [тут](https://github.com/AlexLexx706/guard_bot_firmware):

