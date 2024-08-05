//to know the percentage of result

import java.util.Scanner;

public class result {
    public result() {
    }

    public static void main(String[] args) {
        System.out.println("Enter your marks to get a percentage ");
        System.out.println("enter your english marks");
        Scanner english = new Scanner(System.in);
        float a = english.nextFloat();
        System.out.println("enter your math marks");
        Scanner math = new Scanner(System.in);
        float b = math.nextFloat();
        System.out.println("enter your science marks");
        Scanner science = new Scanner(System.in);
        float c = science.nextFloat();
        System.out.println("enter your social science marks");
        Scanner social_science = new Scanner(System.in);
        float d = social_science.nextFloat();
        System.out.println("enter your hindi marks");
        Scanner hindi = new Scanner(System.in);
        float e = hindi.nextFloat();
        System.out.println("enter your computer marks");
        Scanner computer = new Scanner(System.in);
        float f = computer.nextFloat();
        System.out.println("enter your history marks");
        Scanner history = new Scanner(System.in);
        float g = history.nextFloat();
        float h = a + b + c + d + e + f + g;
        float s = h * 100.0F / 700.0F;
        System.out.print("the percentage of your result is : ");
        System.out.print(s);
    }
}
