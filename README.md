package homwork2;

import java.util.Scanner;

public class test7 {

    public static void main(String[] args) {
Scanner n = new Scanner(System.in);
System.out.print("Enter the number of rows you want in the pyramid  = ");
int x=n.nextInt();
System.out.println("=============================================================================");

for (int i = 0 ; i<x ; i++) {

for (int m = 0 ; m<x-i ; m++) 
    System.out.print(" ");

for (int q = 0 ; q<(i*2+1) ; q++) 
System.out.print("*")  ;   
System.out.println();

}


System.out.println("=============================================================================");
System.out.println("                              Good bay                                     ");        
        
        
        
        
        
        
        
        
        
        
        
        
        
        

    }
    
}
