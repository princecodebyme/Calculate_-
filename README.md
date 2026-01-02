/* this program calculate the % of 5 subject cbse board */ 
import java.util.Scanner;
public class Main {
	public static void main(String[] args) {
	Scanner sc = new Scanner(System.in);
	
	System.out.println("This program was calculate your board %");
	System.out.println("Enter your numbers :");
	int a1 = sc.nextInt();
	System.out.println("Mathmathics : "+a1);
	int a2 = sc.nextInt();
	System.out.println("Science : "+a2);
	int a3 = sc.nextInt();
	System.out.println("Social Science : "+a3);
	int a4 = sc.nextInt();
	System.out.println("Hindi : " +a4);
	int a5 = sc.nextInt();
	System.out.println("English : "+a5);
	int sum = a1+a2+a3+a4+a5;
	float temp = (sum/500.0f)*100;
	System.out.println("Your overall % is : "+temp);	}
}
