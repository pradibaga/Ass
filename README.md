# multiple if,elseif ladder,multipleiftoladder
import java.util.*;
public class Main
{
public static void main(String[] args) {
Scanner sc=new Scanner(System.in);
System.out.print("Enter a number:");
int a=sc.nextInt();
elseifladder(a);
System.out.print("Enter value b:");
int b=sc.nextInt();
System.out.print("Enter value c:");
int c=sc.nextInt();
System.out.print("Enter value d:");
int d=sc.nextInt();
multipleif(b,c,d);
System.out.print("Enter n1:");
int n1=sc.nextInt();
System.out.print("Enter n2:");
int n2=sc.nextInt();
multipleiftoladder(n1,n2);

}
public static void elseifladder(int a)
{
   if (a == 10)
   {
            System.out.println("value is 10\n");
   }


        else if (a == 15)
        {
            System.out.println("value is 15\n");
        }


        else if (a == 20)
        {
            System.out.println("value is 20\n");
        }

        else
        {
            System.out.println("value is not present\n");
        }

}
public static void multipleif(int b,int c,int d)
{
    if(b>10)
    {
        System.out.print("number is greater than 10\n");
    }
    if(c>20)
    {
        System.out.print("number is greater than 20\n");
    }
    if(d>5)
    {
        System.out.print("number is greater than 5\n");
    }
}
public static void multipleiftoladder(int n1,int n2)
{
    if(n1>n2)
    {
        System.out.print(n2 +"is greater\n");
    }
    if(n1<n2)
    {
        System.out.print(n2 +"is greater\n");
    }
    if(n1==n2)
    {
        System.out.print(n1 +n2 +"are equal\n");
    }
}
}
