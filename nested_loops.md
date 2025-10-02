#This file explains nested loops
Nested loops are multiple loops running one after other until completion of main loop
```java
class nested_loops
{
     public static void main(String[]args)
{
     int i,j;
        for(i=1;i<=5;i++)
          {
            for(j=1;j<=4;j++)
          {
            System.out.print("*");
          }
            System.out.print("\n");
          }
}
}
