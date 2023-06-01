# Создать базовый класс «Круг». Элементы класса: поле, задающее радиус; конструктор для инициализации поля (статус доступа protected); функция для вычисления площади круга (площадь круга πr2); функция для печати полей и площади. Создать производный класс «Шар». Элементы класса: конструктор для инициализации поля; переопределенная функция для вычисления объема (вместо площади круга) шара (площадь шара 4/πr3). Создать по одному объекту каждого из классов. Показать вызов созданных функций. При переопределении функций обеспечить динамический полиморфизм, показать его особенности в программе
# 1. Сначала мы объявляем базовый класс "Круг" с защищенным полем "радиус". 
# 2. В конструкторе класса "Круг" мы инициализируем поле "радиус".
# 3. Функция "getArea()" вычисляет площадь круга по формуле πr² и возвращает результат.
# 4. Функция "print()" выводит значения полей объекта и его площадь на экран.
# 5. Затем мы объявляем производный класс "Шар", который наследует все поля и методы базового класса "Круг".
# 6. В конструкторе класса "Шар" мы также инициализируем поле "радиус".
# 7. Функция "getVolume()" переопределяет функцию "getArea()" базового класса и вычисляет объем шара по формуле 4/3πr³.
# 8. В функции "main()" мы создаем объекты классов "Круг" и "Шар" и вызываем их методы "print()".
# https://drive.google.com/file/d/1F4fFliCFTl2li_GrWYjtPOyBxuE2oa7V/view?usp=share_link
