# SOLID
* Принцип единственной ответственности (SRP) - методы, которые описывают разные действия нужно разделять по классам
* Принцип открытости/закрытости (OCP) - не нужно менять сам класс для конкретных условий, лучше его расширить
* Принцип подстановки Лисков (LSP) - класс наследник должен работать также как прорадитель, нельзя нарушать функциональность метода
* Принцип разделения интерфейса (ISP) - интерфейсы нужно разделять на более мелкие, чтобы не было ненужных методов для каких-то случаев
* Принцип инверсии зависимостей (DIP) - в классе не должно быть зависимости от другого класса


User - абстрактный класс. Dog и Student - классы наследнихи. Функциональность методов при наследуемости не была нарушена (LSP). В них только геттеры, сетртеры и метод то стринг (SRP). StudentGroup - класс, в котором также есть геттеры, сеттеры, а также работа ведётся с листом, у которогго данные с типом "студент", при этом данные классы независимы, так как лист создается внутри класса StudentGroup (DIP). OCP - расширять функционал можно в любом классе, создавая класс-наследник.
Интерфейсов в 4 семинаре написано не было, поэтому принцип разделения интерфейса нельзя применить (ISP).