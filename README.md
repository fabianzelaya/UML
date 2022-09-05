# UML

## UML class diagrams
The `Unified Modeling Language (UML)` is a language for software design that uses different types of diagrams to visualize the structure and behavior of programs. A `structural diagram` visualizes static elements of software, such as the variables and methods used in the program. A `behavioral diagram` visualizes dynamic behavior of software, such as the flow of an algorithm.

A UML `class diagram` is a structural diagram that can be used to visually model the classes of a computer program, including member variables and methods.

## UML class diagrams show class names, members, types, and access.

![Screen Shot 2022-09-05 at 2 28 57 PM](https://user-images.githubusercontent.com/71942518/188513880-2155c4df-c3e0-4b18-8c67-cf15e858a8db.png)
1. _One box exists for each class. The class name is centered at the top._

![Screen Shot 2022-09-05 at 2 30 17 PM](https://user-images.githubusercontent.com/71942518/188513981-436be3ae-4b6a-47c9-9347-9a96e82b795f.png)

2. _Class members are listed in the box below. Member variables have a name followed by a colon and the type._

![Screen Shot 2022-09-05 at 2 30 59 PM](https://user-images.githubusercontent.com/71942518/188514030-85bb0823-21c7-45b6-a6af-2125e7fe5989.png)

3. _Each member method's name and return type is listed similarly._

![Screen Shot 2022-09-05 at 2 31 41 PM](https://user-images.githubusercontent.com/71942518/188514082-07e96a31-5438-4bd0-a0bc-7e15cb823a8d.png)

4. _Private and public access is noted to the left of each member. A minus (-) indicates private and a plus (+) indicates public._


## UML for inheritance
UML uses an arrow with a solid line and an unfilled arrow head to indicate that one class inherits from another. The arrow points toward the superclass.

UML uses italics to denote abstract classes. In particular, UML uses italics for the abstract class' name, and for each abstract method in the class. As a reminder, a superclass does not have to be abstract. Also, any class with an abstract method must be abstract.

## UML uses italics for abstract classes and methods.
![Screen Shot 2022-09-05 at 2 39 58 PM](https://user-images.githubusercontent.com/71942518/188514599-6e41da02-86d3-4832-a20e-0b5a09ba84be.png)

| Shape |
| --- |
| +_computerArea(): double_ |
1. Shape is an abstract class, so the class name and abstract method are in italics.

| Shape |
| --- |
| +_computerArea(): double_ |

Circle inherits from Shape: :arrow_up: 

| Circle |
| --- |
| -radius: double |
| -center: Point |
| +computerArea(): double |
2. The solid-lined arrow with an unfilled arrow head indicates that the Circle class inherits from Shape.

3. Circle is a concrete class, so the class name is shown in regular font. Note that Circle implements computeArea().




## Thanks for watching!

If you liked my coding then follow me on my [Instagram](https://www.instagram.com/fabianzelayahn/) account or [GitHub](https://github.com/fabianzelaya) account.

<img src="https://ucarecdn.com/d1a85e63-35f9-41d7-b758-ff05742057d1/GitHub_Black_Signature.png" width="240" height="79.63" />
