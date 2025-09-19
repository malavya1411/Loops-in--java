#For loop application(Countdown)
 Java program that use for loop to display a countdown along with adjustable speed of countdown\
```java
import java.util.*;
public class loop {
    public static void main(String[]args) throws InterruptedException 
    {
        Scanner sc =new Scanner(System.in); 
        System.out.print("Enter The number to start the countdown from: ");
        int m = sc.nextInt();
        for(int i=m ;i>0;i--){
            System.out.println(i);
            Thread.sleep(1000);  // Every Number appears after inputed value here it is 1000ms or 1s
        }
        System.out.print("Happy New Year !!!");
}
}
