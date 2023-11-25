Задача 1 - Абстракция
    � Реализуйте класс Товар, содержащий данные о товаре, 
    и ТорговыйАвтомат, содержащий в себе методы
    initProducts (List <Product>) сохраняющий
    в себе список исходных продуктов и getProduct(String name)

Задача 2 - Инкапсуляция
    � Реализуйте конструкторы, get/set методы,
    постройте логику ТорговогоАвтомата на основе кода
    сделанного в предыдущем задании

Задача 3 - Наследование
    � Сделайте класс Товар абстрактным, создайте нескольких 
    наследников (к примеру: БутылкаВоды),
    сделайте интерфейсом ТорговыйАвтомат и реализуйте класс 
    какого-то одного типа
    ТорговогоАвтомата (пример: ПродающийБутылкиВодыАвтомат)

Задача 4 - Полиморфизм
    � Переопределите метод toString для Товара,
    запустите программу, после этого переопределите для
    наследника этот метод, после запуска обратите внимание
    на изменение поведения.
    � Создайте перегруженный метод выдачи товара ТорговымАвтоматом
    дополнив дополнительным
    входным параметром (пример: getProduct(String name) выдающий товар
    по имени, создайте метод
    возвращающий товар по имени и какому-либо параметру товара
    getProduct(String name, int volume)

    Домашнее задание
    � Создать наследника реализованного класса ГорячийНапиток с дополнительным полем int
    температура.
    � Создать класс ГорячихНапитковАвтомат реализующий интерфейс ТорговыйАвтомат и реализовать
    перегруженный метод getProduct(int name, int volume, int temperature) выдающий продукт
    соответствующий имени, объему и температуре
    � В main проинициализировать несколько ГорячихНапитков и ГорячихНапитковАвтомат и
    воспроизвести логику заложенную в программе
    � Все вышеуказанное создать согласно принципам ООП пройдённым на семинаре
