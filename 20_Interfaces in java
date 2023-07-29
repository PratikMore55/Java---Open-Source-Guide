package com.company;

interface Bicycle{
    int a = 64;
    void applyBrake(int decrement);
    void speedUp(int increment);
}

 class AvonCycle implements Bicycle {
     void blowHorn() {
         System.out.println("Honk");
     }

     public void applyBrake(int decrement) {
         System.out.println("Applying Brake");
     }

     public void speedUp(int increment) {
         System.out.println("Increasing Speed");
     }
 }
public class Interfaces {
    public static void main(String[] args) {
        AvonCycle cycle = new AvonCycle();
        cycle.applyBrake(1);
        cycle.blowHorn();
        cycle.speedUp(3);

        //cycle.a = 64;          // You cannot modify the properties in Interface as they are final

        System.out.println(cycle.a);
    }
}
