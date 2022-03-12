# try-and-catch
import java.util.*;
class Main 
{
    public static void main(String args[])
    {
        Scanner s=new Scanner(System.in);
        try {
        int k;
        System.out.println("enter the size of an array:");
        k=s.nextInt();
        int a[]=new int[k];
        if(a.length>0)
        {
            System.out.println("the size of the array:"+a.length);
        }
        else
        {
            throw new Exception("java.alng.NegativeArraySizeException");
        }
    }
    catch(Exception e)
    {
        System.out.println(e);
    }
    }
}
