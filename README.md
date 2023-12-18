package lessen;

import java.util.Scanner;

public class mean {
    public static void main(String[] args){
        String name;
        int code;
        String gender;
        String position;
        float salary;
        Scanner objin = new Scanner(System.in);
        System.out.print("Enter Code : ");
        code=objin.nextInt();
        objin.nextLine();
        System.out.print("Enter Name : ");
        name=objin.nextLine();
        System.out.print("Enter Gender : ");
        gender=objin.nextLine();
        System.out.print("Enter Position : ");
        position=objin.nextLine();
        System.out.print("Enter Salary : ");
        salary=objin.nextFloat();
        
        
        System.out.println("Code     : "+ code);
        System.out.println("Name     : "+name);
        System.out.println("Gender   : "+gender);
        System.out.println("Position : "+position);
        System.out.println("Salary   : $"+salary);
    }
}
