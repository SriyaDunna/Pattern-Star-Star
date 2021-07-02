# Pattern-Star-Star
import java.util.Scanner;
class Pattern
{
public static void main(String args[])
{
    Scanner s = new Scanner(System.in);
    int i,j,rows = 5;
    for(i=0;i<=rows-1;i++)
    {
        for(j=0;j<=i;j++)
        {
        System.out.print("*"+ " ");
    }
    System.out.println();
    }
    for(i=rows-1;i>=0;i--)
    {
        for(j=0;j<=i;j++)
        {
            System.out.print("*"+ " ");
        }
        System.out.println();
        }
    }
}
