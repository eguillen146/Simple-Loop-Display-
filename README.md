# Simple-Loop-Display-
import java.ui;

// Simple pattern out put 

public class pattern
{
  public static void main(String args[])
  {
    int i,j;
     for(i=0; i<10; i++)
     {
        for(j=0; j<i; j++)
        {
            System.out.print("* ");
        }
        System.out.println(" ");
     }
     
    
      
     
     
     
     
     int k,t;
         
         for(k=0; k<10; k++)
         {
             for(t=10; t>k; t--)
             {
                 System.out.print("* ");
             }
             System.out.println(" "); 
         }
     
    }
  }
