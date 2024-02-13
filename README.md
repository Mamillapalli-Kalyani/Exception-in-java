# Exception-in-java
public class Main
{
  public static void main(String args[])
  {
    int a=10,b=20,c;
    int as1[]={1,2};
    try
    {
       System.out.println(as1[9]);
       c=a/b;
       System.out.println(c);
    }
    catch(ArithmeticException e)
    {
      System.out.println("You got error");
    }
    catch(Exception e)
    {
      System.out.println(e.getMessage());
    }
  }
}
