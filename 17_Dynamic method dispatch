package com.company;
class One{
    public void greet(){
        System.out.println("Namaste");
    }
    public void name(){
        System.out.println("My name is java");
    }
}

class Two extends  One{
    public void swagat(){
        System.out.println("Aapka swagat hai");
    }
    public void name() {
        System.out.println("My name is java in class 2");
    }
}
public class Dynamic_method_dispatch {
    public static void main(String[] args) {
//        One obj = new One();
//        Two tobj = new Two();
//        obj.name();

        One obj = new Two();
        // Two tobj = new One();        // Not allowed

        obj.greet();
        obj.name();
    }
}
