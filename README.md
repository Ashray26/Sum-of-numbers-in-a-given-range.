import java.util.*;
public class Main{
    public static void main(String args[])
    {
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter the number1:-");
        int num1=sc.nextInt();
        System.out.println("Enter the number2:-");
        int num2=sc.nextInt();
        
        int sum=0;
        
        for(int i=num1;i<=num2;i++)
        {
            sum=sum+i;
        }
        System.out.println(sum);
    }
}
