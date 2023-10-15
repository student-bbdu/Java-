# Java-
#Swap of two number in java
import java.util.Scanner;
public class SwapOfNumber {
    public static void main(String[] args) {
    Scanner sc=new Scanner(System.in);
         int x,y,t;
          System.out.println("Enter the value of X And Y : ");
          x=sc.nextInt();
          y=sc.nextInt();
          System.out.println("Before Swapping : "+x + " "+y);
          t=x;
          x=y;
          y=t;
         System.out.println("After Swapping : "+x + "  "+y);
    }
}
