import java.util.Scanner;
import java.util.ArrayList;
import java.util.List;

class EmpMain {
    public static void main(String[] args) {
        List<Emp> list = new ArrayList<Emp>(5);
        list.add(new Emp(20, "WuTao", 3000));
        list.add(new Emp(21, "Bill", 2000));
        list.add(new Emp(19, "Bob", 3500));
        list.add(new Emp(22, "Jhon", 3000));
        list.add(new Emp(21, "Mick", 3000));

        Scanner sc = new Scanner(System.in);

        while (true) {
            System.out.println("Please input the name: ");
            String key = sc.nextLine();
            for (int i = 0; i < 5; i++) {
                Emp emp = list.get(i);
                if (emp.getName().equals(key)) {
                    System.out.println("["+i+"] name: "+emp.getName()+" age: "+emp.age+" sal: "+emp.sal);
                }
            }
        }

    }
}

class Emp {
    public int age;
    public String name;
    public int sal;

    Emp(int age, String name, int sal) {
        this.age = age;
        this.name = name;
        this.sal = sal;
    }

    public String getName() {
        return this.name;
    }
}
