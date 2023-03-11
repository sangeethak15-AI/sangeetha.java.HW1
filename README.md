# sangeetha.java.HW1
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











