import java.io.Console;
import java.util.Scanner;

public class Session_2_IfClass_Assignment_1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner scan = new Scanner(System.in);
		System.out.println("Enter your age in integer form only");
		int age=scan.nextInt();
		
		if (age >= 18 ){
			
			System.out.println("You are eligible to vote.");
		}
		else{
			System.out.println("you are not eligible to vote");
		}
		scan.close();
	}

}
