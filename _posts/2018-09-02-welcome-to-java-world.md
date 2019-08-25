---
layout: post
title: "Welcome to Java World"
date: 2018-09-02
---

Java is a higher level language which during compilation, is broken to lower language and then to machine language. It is object oriented as we declare classes , create objects of these classes etc, i.e, Object Oriented Programming. Java follows the motto "Write Once , Run Anywhere". Java Virtual Machine (JVM) is a abstract virtual machine present in the real machine which can compile java programs and also those in other languages.

 

All the data provided are called attributes or fields while the procedures to make use of them are called methods.

Class is the blueprint while object is an instance of the class. Constructor is similar to method but it is used to initialize the attributes of the objects but doesn't return anything.

 

Java has many special properties like Encapsulation, Inheritance, Polymorphism etc. Encapsulation can be imagined as a blanket /a house covering the entities i.e, wrapping data, functions etc into a single unit.

Inheritance is about inheriting attributes and methods of one class in another. The property is true to its word meaning. 

Property of polymorphism can be compared to Mystique in X-Men - one name , different forms. An example is given below.

 

    public class Hello {
          int a;
          String b;
          
          public Hello( ){
                        a = 0 ;
                       b = null;
         }

         public Hello(int a , String b){
                        this.a = a;
                        this.b = b;
        }

         public static void main(String[] args) {
                              System.out.println("Hello World");
        }

    }

 

Here Hello( ) and Hello(int a , String b) are the constructors. Here the form is the same i.e, initialize the attributes but the form is different i.e, the arguments passed is different. The first one has no arguments. This is a default constructor. If we are not passing any arguments i.e,we do not want to initialize the attributes using constructors , default constructors initialize them to null. At that time we do not have to define the constructor, else we will have to define it.

 

Also while passing arguments, if both the arguments and the attributes have the same name , we use this keyword to differentiate attribute from the argument.

 

Another important concept under Java is Access Modifiers.

Access modifiers are of 3 types : public , private and protected. public can be accessed outside the class by other classes while private can be accessed only within the class and

protected can be access outside the class but then we have to create an object of that class to access it.

 

    public class Hello{
           public static void main( ){
                 System.out.println("Hello World");
           }
    }

 

Here class named Hello is created. This program prints Hello World on the terminal.

 

main is required while running a program. It's the entry point of a program, i.e, let's imagine a hostel scene where you are allowed to go out during weekends only if you have gate pass. So the security at the gate is JVM here. He checks whether you have gate pass and then lets you through.Similarly JVM checks if the main is present in the given code and then it'll run.

 

Java has a really good advantage. There are times when we declare new objects but they go neglected by us and are not used in the program.This leads to more memory usage but Java takes care of this. These objects get destroyed by the Garbage Collector thus helping in memory efficiency.

 

So,

Happy Coding folks :)
