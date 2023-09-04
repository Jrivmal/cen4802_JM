# cen4802_JM
Fibonacci 
Janet Malavet
/**
	 * 
	 * @param n - the nth fibonacci sequence
	 * @param (n <=1) - if n=1 or fewer, then return n
     * recursively bring the function fibonacci
       * main method
       * @param args
    	 * param n - declare variable n
    	   * create scanner class object
    	   * get value of n
    	   * @return - print nth number in sequence
    	*/
    	import java.util.*;
public class firsmethod
{
      public static int fibonacci(int n)
    {    	  
    	     if (n <= 1)
       return n;
     
     return fibonacci(n-1) + fibonacci(n-2);
    }
    
    public static void main (String args[])
    {        	
      int n;  
    Scanner scnr=new Scanner(System.in);   
    System.out.println("Enter value of n: ");
    n=scnr.nextInt();   
     System.out.println("The "+n+"th term of the Fibonacci sequence is "+fibonacci(n));
}
}
