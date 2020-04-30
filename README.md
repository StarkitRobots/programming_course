# Програмирование на Python: классы и визуализация
В курсе будет рассмотрено применения классов в языке Python для создания физического симулятора. Будет представлен пример использования объектно-ориентированного подхода к построению программ, изучены базовые приемы проектирования гибкой и расширяемой архитектуры. На лекциях планируется ознакомление с библиотекой OpenCV, методами визуализации и последовательной реализации системы с желаемым поведением.
## Лекции на youtube: 

  - Часть 1 - https://youtu.be/y_uC8589TlA 
  - Часть 2 - https://youtu.be/0ynFtoNf6uc
  
  *You are here*
  - Часть 3 - https://youtu.be/ZurljLuN5pk
  - Часть 4 - https://youtu.be/eH2BAsjzBD0

## План курса

  1) На лекции будут рассмотрены основные понятия компьютерного зрения (представление изображения в компьютере, фильтры), рисование графических примитивов с помощью библиотеки OpenCV, будет рассказано о месте зрения в программном комплексе гуманоидного робота и связи с другими модулями. Будет кратко рассказано о базовых и производных классах (с одновременной демонстрацией процесса написания кода), будет реализован простой физический симулятор с несколькими типами фигур (круг, квадрат, треугольник, линия), отталкивающимися от стен. Будут изложены методы наглядной визуализации на примере связи координаты и цвета, а также обработка простых сигналов с клавиатуры.
    ![](imgs/lines.jpg)

  2) В симулятор будет добавлен эффект гравитации, отслеживание с помощью графиков кинетической, потенциальной и полной энергии в режиме реального времени. Будет дан обзор физических моделей столкновений объектов (реализация планируется на 3 лекции). Будут даны примеры использования лямбда-функций и функций как параметров для вычисления цвета как функции координат и скоростей. Будет рассказано о типах данных, будут введены вещественные скорости объектов, генерация объектов произвольного типа с произвольными характеристиками. Будут изложены предпосылки к введению дополнительного уровня абстракции для удобства работы с объектами любого типа (реализация планируется на 3 лекции).
  
  3) На лекции будут рассмотрены модели освещения и реализована модель освещение Ламберта. Будет дано понятие поверхности с точки зрения визуализации, будет построена модель точечного источника света. Планируется написание программы, позволяющей изменять положение источника света с одновременной визуализацией результата. Если останется время, будет реализована модель освещения плоскости.
  ![](imgs/3d_balls.jpg)

  4) На лекции будут рассмотрены методы оптимизации построения освещения, в том числе триангуляция, игнорирование закрытых областей, предподсчет различных состояний объектов и использование симметрий для уменьшения вычислительной сложности процесса.
