# Java-Code-
//Sum of Array in Java 
// using method := With Parameter and Without Return values 
// Also user-defined values in array 

import java.util.Scanner;

public class Assignment4 {

    public static void main(String[] args) {
        
        Scanner A= new Scanner(System.in);

# values for how many elements you want by users 

        int values=10;
        int[] array= new int[10];



 # this loop for taken user-defined values .

        System.out.println("Enter The Array Value here : ");
        for (int i = 0; i < values; i++) {                         
            array[i]=A.nextInt();
        }

        System.out.println();
# //this loop use for print user-defined values 
        for (int i = 0; i < array.length; i++) {
            System.out.print(array[i ] + " ");
        }

        System.out.println();

 # ///sum use for addition of elements 

        int sum=0;
        for(int i=0; i<array.length; i++){
         sum+= array[i];
        }
        
        System.out.println();

        System.out.println(sum);

    

    }
}




