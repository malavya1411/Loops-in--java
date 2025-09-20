# Fibonacci Series in java
This java program gives fibonacci series uptil the no of terms entered by users
 ```java
import java.util.*;
public class fibonacci
{
  public static void main(String[] args)
{
    int n ;
    int firstterm;
    int secondterm;
    Scanner sc = new Scanner(System.in);
    System.out.print("Enter number of terms in the series:");
    n=sc.nextInt();
    firstterm = 0;
    secondterm = 1;
    System.out.println("Fibonacci Series till " + n + " terms:");

    for (int i = 1; i <= n; ++i) {
      System.out.print(firstterm + ", ");

      // compute the next term
      int nextterm = firstterm + secondterm;
      firstterm = secondterm;
      secondterm = nextterm;
    }
  }
}
