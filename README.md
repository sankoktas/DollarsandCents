# DollarsandCents
This program reads a price and prints the dollars and cents.

import java.util.Scanner;
public class KFS_DollarsAndCents_Main

{
    public static void main (String [] args)
    
    {
       Scanner in = new Scanner(System.in);
       System.out.print("Enter the price: ");
       double price = in.nextDouble(); //Receives the price input
       
       int dollars = (int) price; //Calculates the dollars
       int cents = (int)((price - dollars)* 100 + 0.5); //Calculates the cents
        
       System.out.print("The price is " + (dollars) + " dollars and " + cents + " cents.");
    }
    
}
