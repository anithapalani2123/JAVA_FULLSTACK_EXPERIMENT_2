# JAVA_FULLSTACK_EXPERIMENT_2
## AIM:
   To compare two numbers using java
## PROCEDURE:
### 1.Create the main class and declare the main methoda sothat the program will be recognised by JVM to run.
### 2.Declare two variables along with proper data type.
### 3.Use 'if' consition to check their values and find the greater number.
### 4.Print the output using 'System.out.print'.
### 5.The program will be executed after compiling them.


## PROGRAM:
```
import java.util.Scanner;
public class compare_num
{
    public static void main(String args[])
    {
        Scanner sc = new Scanner(System.in);
        System.out.print("Enter first number: ");
        int a = sc.nextInt();
        System.out.print("Enter second number: ");
        int b = sc.nextInt();
        compare(a,b);
    }
    public static void compare(int n1,int n2)
    {
        if(n1 > n2)
        {
            System.out.println(n1+" greater than "+n2);
        }
        else if(n2 > n1)
        {
            System.out.println(n2+" greater than "+n1);
        }
        else
        {
            System.out.println("Both the numbers are equal");
        }
    }
}
```
## OUTPUT:
![image](https://github.com/anithapalani2123/JAVA_FULLSTACK_EXPERIMENT_2/assets/94184990/2da5303e-7ba5-4ef7-9cde-3855335e888d)

## RESULTS:
Hence the program is executed successfully and the output is obtained for comparing two numbers.














