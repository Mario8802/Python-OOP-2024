# Theory tests

- [First Steps In OOP](https://forms.gle/jenahYVLxPK8PYhN6)

- [Classes and Objects](https://forms.gle/PeoSqmdHyCJbptxP8)

---

# Plans

### 01. First Steps In OOP

1. Какво е **namespace**?
   - Пространство, в което са дефинирани обекти
   - Видове:
     - Built-In
     - Global
     - Local

2. Какво е **scope**?
   - Поле на действие, в което един обект е достъпен
   - Видове:
     - Built-In
     - Global
     - Enclosing
     - Local

3. Обекти
   - **Всичко в Python е обект**
   - Обектите се състоят от две основни части:
     - Характеристики (State)
     - Поведение (Behavior)
  ```py
    class MyObject:
        def __init__(self, property1):
            self.property1 = property1  # State

        def doSomething():  # Behavior
            ...
  ```

---

### 02. Classes and Objects

1. Атрибути
   - Data Attributes
     - Instance Attributes -
       - Закачени на инстанцията(self)
       - Уникални за всяка инстанция
     - Class Attributes
       - Закачени на класа
       - Споделени между всички инстанции
   - Methods
     - Функции принадлежящи на класа
    
2. Магически методи
   - **__init__** - използваме за инстанциране на класа
   - **__str__** - използваме за стрингова репрезентация на класа (т.е. вместо <object in memory ...>); извиква се, когато се опитаме да кастнем инстанция към стринг
   - **__repr__** - използваме, за да представим класа като стринг дори при дебъгване (машинна репрезентация)
   - **__dict__** - репрезентира стейта на класа като dictionary
   - **__doc__** - връща документацията на обекта 

---
