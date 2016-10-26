# OOAD-WEEK09 HOMEWORK
## Class DIAGRAM

  Class 1
  Code
```
@startuml
class Car

Driver - Car : drives >
Car *- Wheel : have 4 >
Car -- Person : < owns

@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK09/blob/master/Homework09/Class1.png?raw=true">

----------------------------------------------------------------

    Class 2
    Code
```
@startuml
Computer <|-- Mainboard

Computer : Moniter()
Mainboard : Computer[] CPU
Mainboard : Ram()

@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK09/blob/master/Homework09/class2.png?raw=true">

----------------------------------------------------------------

    Class 3
    Code
```
@startuml

class Object
class Object2

Object2 *-- Object

hide Object2

@enduml

```
<img src="https://github.com/Mustted/OOAD-WEEK09/blob/master/Homework09/class3.png?raw=true">

----------------------------------------------------------------

    Class 4
    Code
```
@startuml

class Object<? extends Project> {
  int size()
}
Object *- Project

@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK09/blob/master/Homework09/class4.png?raw=true">

----------------------------------------------------------------

    Class 5
    Code
```
@startuml
Room o- Teacher
Room *-- Table
@enduml
```
<img src="https://github.com/Mustted/OOAD-WEEK09/blob/master/Homework09/class5.png?raw=true">

----------------------------------------------------------------
