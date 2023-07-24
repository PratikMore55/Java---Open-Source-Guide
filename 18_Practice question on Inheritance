package com.company;

class Circle{
    public int getRadius() {
        return radius;
    }

    public void setRadius(int radius) {
        this.radius = radius;
    }

    public int radius;
    Circle(int r){
        System.out.println("I am a circle parameterized constructor");
        this.radius=r;
    }
    public double area(){
        return Math.PI*this.radius*this.radius;
    }
}

class Cylinder extends Circle{
    public int height;
    Cylinder(int r, int h){
        super(r);           // When we use super keyword so we basically call the constructor which passes an integer value in it
        System.out.println("I am a cylinder parameterized constructor");
        this.height=h;
    }

    public int getHeight() {
        return height;
    }

    public void setHeight(int height) {
        this.height = height;
    }

    public double volume(){
        return Math.PI*this.radius*this.radius*this.height;
    }
}
public class practiceset5 {
    public static void main(String[] args) {

        // Problem 1

        //Circle objC = new Circle(8);
        Cylinder obj = new Cylinder(8,4);
    }
}
