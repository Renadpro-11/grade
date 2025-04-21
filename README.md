package practiceHome;
import java.util.Scanner;
public class gradd {

	public static void main(String[] argms) {
		Scanner input = new Scanner(System.in);
		System.out.println(" Enter your grade ");
		char grade = input.next().charAt(0);
		
		switch(grade) {
		case 'A':
			System.out.println(" Excellent ");
			break;
		case 'B':
			System.out.println(" Very Good ");
			break;
		case 'C':
			System.out.println(" Good ");
			break;
		case 'D':
			System.out.println(" pass ");
			break;
		case 'F':
			System.out.println(" fail ");
			break;
	  default:
		  System.out.println("Invalid grade");
		}
		
		
		
	}
	
	
}
