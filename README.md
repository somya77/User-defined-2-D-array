# User-defined-2-D-array
import java.util.Scanner;
class Test12
{
 public static void main(String args[])
{
 System.out.println("Enter values");
 Scanner obj=new Scanner(System.in);
 int num[][]=new int[3][4];

for(int i=0;i<3;i++)
{
 for(int j=0;j<4;j++)
{
  num[i][j]=obj.nextInt();
}
}
 System.out.println("You Entered");
for(int i=0;i<3;i++)
{
 for(int j=0;j<4;j++)
{
   System.out.print(num[i][j]+" ");
}
 System.out.println();
}
}
}

