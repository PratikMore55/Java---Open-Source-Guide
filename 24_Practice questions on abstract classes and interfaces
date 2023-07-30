package com.company;

abstract class Pen{
    abstract void write();
    abstract void refill();
}

class FountainPen extends Pen{
    void write(){
        System.out.println("Writing");
    }
    void refill(){
        System.out.println("Refilling");
    }
    void changeNib(){
        System.out.println("Changing Nib");
    }
}
class Monkey{
    void jump(){
        System.out.println("Jumping");
    }
    void bite(){
        System.out.println("Biting");
    }
}
interface BasicAnimal{
    void eat();
    void sleep();
}
class Human extends Monkey implements BasicAnimal{
    void speak (){
        System.out.println("Salam valikum");
    }
    public void eat(){
        System.out.println("Eating");
    }
    public void sleep(){
        System.out.println("Sleeping");
    }
}
public class practice_set_4 {
    public static void main(String[] args) {
        FountainPen fp = new FountainPen();
        fp.changeNib();

        Human pm = new Human();
        pm.sleep();

        Monkey m1 = new Human();    // Polymorphism
        m1.bite();
        m1.jump();
    }
}
