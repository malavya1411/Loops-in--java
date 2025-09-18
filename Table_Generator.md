# Table Generator from 1 to 10 of any number
Application of do_while loop in java in form of table genearot of any number from 1 to 10
```java
import java.util.*;
public class loop_in_java 
{
    public static void main(String[]args)
    {
     int i,a;
     Scanner sc = new Scanner(System.in);
     System.out.print("Enter an Number:");
     a=sc.nextInt();
     i=1;
     do
     {System.out.println(a + " X "+i + " = " + (i*a));
       i++;
     }
     while(i<=10);
     }
}

    
