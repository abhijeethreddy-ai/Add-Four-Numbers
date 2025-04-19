# Add-Four-Numbers

package day3;

import java.util.Scanner;

public class AddFourNumbers {

	public static void main(String[] args)
	
	{

		Scanner scanner = new Scanner(System.in);

        // Input 4 numbers from user
        System.out.print("Enter the first number: ");
        int num1 = scanner.nextInt();

        System.out.print("Enter the second number: ");
        int num2 = scanner.nextInt();

        System.out.print("Enter the third number: ");
        int num3 = scanner.nextInt();

        System.out.print("Enter the fourth number: ");
        int num4 = scanner.nextInt();

        // Calculate the sum
        int sum = num1 + num2 + num3 + num4;

        // Display the result
        System.out.println("The sum of the 4 numbers is: " + sum);

        scanner.close();
  
		
		
	}

}
