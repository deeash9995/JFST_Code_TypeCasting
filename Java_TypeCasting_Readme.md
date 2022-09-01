Java Variable Type Conversion & Type Casting
A variable of one type can receive the value of another type. Here there are 2 cases –

Case 1) Variable of smaller capacity is being assigned to another variable of bigger capacity.

    Eg: 
        double d;
        int i = 9;
        d = i;
This process is Automatic, and non-explicit is known as Conversion

Case 2) Variable of larger capacity is being assigned to another variable of smaller capacity

    Eg:
        double d = 9;
        int i;
        i = (int)d;

In such cases, we have to explicitly specify the type cast operator'()'. This process is known as Type Casting.

In Java, there are two types of casting:

--> Widening Casting (automatically) - converting a smaller type to a larger type size
        byte -> short -> char -> int -> long -> float -> double

--> Narrowing Casting (manually) - converting a larger type to a smaller size type
        double -> float -> long -> int -> char -> short -> byte

Task : 

        1. Consider two containers, Solid and Liquid with volume as its property

        2. Perform a **narrow type casting** of the value of the container's 'volume' and display the value

        3. Similarly create properties of other types for the containers and perform narrow and wide type casting and display the values.