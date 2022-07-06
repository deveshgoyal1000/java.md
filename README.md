# java


Q/Program-1
Create a program to convert temperature in celsius to fahrenheit.

The formula to convert Celsius to Fahrenheit is

fahrenheit = (celsius * 1.8) + 32
Get temperature in Celsius input from the user and store it in the celsius variable.
Convert the temperature to Fahrenheit using the above formula and store it in the fahrenheit variable.
Print the temperature in fahrenheit.
Example
Test Input

35.5
Expected Output

95.9
// program starting
import java.util.Scanner;

class Main {
    public static void main(String[] args) {

        // create object class of Scanner class 
        Scanner input = new Scanner(System.in);
        
        // take temperature in degree celsius from the user
        System.out.println("Enter the value in celsius: ");
        
        double celsius = input.nextDouble();
        
 
        // convert degree to fahrenheit
        double fahrenheit = (celsius * 1.8) + 32;
        
 
        // print degree in fahrenheit
        System.out.println("Value of degree celsius into fahrenheit is: " + fahrenheit);
    }
}
