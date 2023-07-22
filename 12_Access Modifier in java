class MyEmployee{
    private int id;
    private String name;
    public String getName() {
        return name;
    }
    public void setName(String n){
        name = n;
    }
    public int setId(int i){
        this.id = i;
        return i;
    }
    public int getId(){
        return id;
    }
}

public class AccessModifiers {
    public static void main(String[] args) {
        MyEmployee gg = new MyEmployee();
//                gg.id=29;
//                gg.name="GG";      // Throws an error due to private access modifier
        gg.setName("GG");
        gg.setId(99);
        System.out.println(gg.getName());
        System.out.println(gg.getId());
    }
}
