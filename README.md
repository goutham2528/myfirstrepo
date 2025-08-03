# myfirstrepo
this is my first repo ever in git-hub
import java.util.Scanner; // Import the Scanner class for user input

public class SampleProgram {
    public static void main(String[] args) {
        // Create a Scanner object to read input
        Scanner scanner = new Scanner(System.in);

        // Print a welcome message
        System.out.println("Welcome to the Java Sample Program!");

        // Ask the user for two numbers
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        // Perform addition
        int sum = num1 + num2;

        // Display the result
        System.out.println("The sum of " + num1 + " and " + num2 + " is: " + sum);

        // Close the scanner
        scanner.close();
    }
}
