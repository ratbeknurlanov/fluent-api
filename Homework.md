# Задача ObjectPrinting

Разработать библиотеку для преобразования любого объекта в строку, перечисляя значения публичных свойств и полей объекта.
 
Все должно гибко настраиваться. А именно:
 1. Исключить из сериализации свойства определенного типа
 2. Указать альтернативный способ сериализации для определенного типа
 3. Для числовых типов указать культуру
 4. Настроить сериализацию конкретного свойства
 5. Настроить обрезание значений строковых свойств
 6. Исключить из сериализации конкретное свойство

Также от решения ожидается:
 1. Поддержка коллекций (массивы, списки, словари*, ...)
 2. Корректная обработка циклических ссылок между объектами (не должны приводить к `StackOverflowException`)