import java.util.Arrays;
import java.util.Scanner;
public class o01
{
   public static void main(String[] args)
   {
	   Scanner cin  = new Scanner(System.in);
	   int a = cin.nextInt();
	   int b = cin.nextInt();
	   int c = cin.nextInt();
	   int x[] = {a,b,c};
       Arrays.sort(x);
       a = x[0];
       b = x[1];
       c = x[2];
	   System.out.println(a+" "+b+" "+c+" ");
	   if(a+b<=c)
	   {
		 System.out.println("No");
	   }
	   else if(a*a + b*b<c*c)
	   {
		 System.out.println("Obtuse");
	   }
	   else if(a*a + b*b == c*c)
	   {
		 System.out.println("Right");
	   }
	   else
	   {
		System.out.println("Acute");
	   }
	   cin.close();
   }
   
}
