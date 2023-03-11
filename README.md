# Java Homework
## 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        float divide;
        Scanner sc=new Scanner(System.in);
        int ab=sc.nextInt();
        int cd=sc.nextInt();
        int add=ab+cd;
        int sub=ab-cd;
        int prod=ab*cd;
        divide=ab/cd;
        int rem=ab%cd;
        System.out.println("Sum = "+add);
        System.out.println("Subtraction = "+sub);
        System.out.println("Product = "+prod);
        System.out.println("Division = "+divide);
        System.out.println("Remainder = "+rem);
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224467351-8f01f4ba-fac4-4334-841a-11e30895c32c.png)


## 2.Write a Java program to compare two numbers
```
import java.util.Scanner;
public class Main{
        public static void main(String[] args) {
            Scanner sc=new Scanner(System.in);
            int a=sc.nextInt();
            int b=sc.nextInt();
            if(a==b)
                System.out.println("Equal");
            else if(a>b)
                System.out.println("Greater");
            else if(a<b)
                System.out.println("Smaller");
            else if(a!=b)
                System.out.println("Not Equal");
        }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224467649-020cf981-1058-4347-a0f1-fa04812015fe.png)


## 3. Write a Java program to convert a string to an integer
```
public class Main{
    public static void main(String[] args) {
        int num=Integer.valueOf("-895");
        System.out.println("Number is = "+num);
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224467880-fa9ebef6-13fb-4605-aa7a-08a1c87dc561.png)


## 4.Java Program to find area of rhombus
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Diagonal 1: ");
        int d1 =sc.nextInt();
        System.out.println("Diagonal 2: ");
        int d2 =sc.nextInt();
        int Area=(d1*d2) / 2;
        System.out.println("Area of the Rhombus = " + Area);
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224471096-f5a30d3a-2f39-4c4f-af8a-e88971ae632a.png)


## 5.Write a Java program to find the number of days in a month.
```
import java.util.Scanner;
public class Main{
    public static void main(String[] args){
    Scanner sc=new Scanner(System.in);
    System.out.print(" Enter a Month Number:");
    int month=sc.nextInt();
    if (month == 1 || month==3 || month==5|| month==7 || month==8 || month == 10 || month==12){
        System.out.println("In 31 Days in this Month");
    }
    else if (month == 4 || month==6 || month==9 || month == 11) {
        System.out.println("\n 30 Days in this Month");
    }
    else if (month == 2) {
        System.out.println("\n 28 Days in this Month");
    }
    else{
        System.out.println("\n Please enter Valid Number between 1 to 12");
    }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224471728-4a0b3899-39bc-44fd-9bf5-0d9b46acd520.png)


## 6.Write a Java program to print the even numbers from 1 to 20
```
public class Main {
    public static void main(String[] args) {
        int i;
        for (i=1;i<=20;i++)
            if(i%2==0){
                System.out.println(i);
            }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224471948-9a563b5b-9ee5-406a-b7f8-69caf5389c1d.png)


## 7.Write a Java program to create a simple calculator
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the choice(1-4):");
        int ch = sc.nextInt();
        System.out.println("Enter the 1st Number: ");
        int num1 = sc.nextInt();
        System.out.println("Enter the 2nd Number: ");
        int num2 = sc.nextInt();
        if (ch == 1) {
            int add = num1 + num2;
            System.out.println("Sum = " + add);
        } else if (ch == 2) {
            int sub = num1 - num2;
            System.out.println("Difference = " + sub);
        } else if (ch == 3) {
            int mul = num1 * num2;
            System.out.println("Product = " + mul);
        } else {
            int div = num1 / num2;
            System.out.println("Division = " + div);
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224472221-fbb67160-367c-4afb-9a46-2ec8f803ec37.png)


## 8.Write a Java program to print multiplication table of given number
```
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the number: ");
        int n = sc.nextInt();
        int i;
        for (i = 1; i <= 10; i++) {
            System.out.println(n + " * " + i + " = " + n * i);
        }
    }
}
```
## Output:
![image](https://user-images.githubusercontent.com/93992063/224472707-1c2c1721-1c27-4ef8-ba84-6c9eccbd91be.png)












