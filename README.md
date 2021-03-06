# case-spectrometer
Корпус для монтирования сцинтилляционного гама-спектрометра основанного на ФЭУ-85 в короб. Обеспечивает плотный прижим кристалла к фотоэлектронному умножителю.

В данном репозитории находятся:
- описание 
- 3D модели для сцинтилляционного гама-спектрометра в форматах
  - программы Fusion360 ```.f3z```
  - универсальном формате САПР ```.step```
  - полигональном формате ```.stl``` для 3d печати.
- инструкция по сборке.

## описание

Сборка по сути представляет из себя фитинг, где в одной его части закреплен ФЭУ, а в другой кристалл сцинтиллятора. Обе эти части могут продольно перемещаться вдоль оси, но зафиксированы от вращения с помощью стоек, монтируемых в короб. Гайка при вращение перемещается по резьбе вокруг фэу и поджимает колпак с кристаллом, обеспечивая плотный контакт ФЭУ и сцинтиллятора.

## инструкция по сборке

Для печати нужно загрузить модели в формате ```.stl```. В директории ```\Images``` можно посмотреть оптимальную ориентацию моделей при использовании FDM печати.
В детали ```symetric side``` после печати нужно досверлить отверстия сверлом 3mm.

### порядок сборки
![Alt-текст](https://github.com/fmtrifonov/case-spectrometer/blob/main/Images/parts.png "Сборка в разрезе")

На ФЭУ(1) установить деталь(8) и (4) как на рисунке.
Затем надевается гнездо питания(5) и деталь (8) фиксируется боковинками (7) снизу и сверху. 
В стакан (3) вставляется сцинтиллятор прозрачной стороной наружу. На него наносится оптическая смазка.
Стакан (3) навинчивается на болт (4) с запасом по ходу ~пол оборота. Прим. Запас хода оценивается расстоянием, которое пройдет кристалл до касания с ФЭУ, а не виднеющейся частью наружной резьбы.
К стакану прикручиваются ножки (9), а боковинки закрепляются ножками (6). Ножки (6) и (9) выравниваются в горизонталь (так, чтобы сборку можно было вставить в короб(10)), после чего гайка (4) закручевается до упора. 
ВНИМАНИЕ!!! Не переусердствуйте с затяжкой. В лучшем случае повредите печатные детали, в худшем - лопнет ФЭУ.
