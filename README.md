import java.util.*;
public class Ivan1 
{
	public static void main(String[] args)
	{
		Scanner in = new Scanner(System.in);
		System.out.println("Hi there! Please enter userName!");
		String userName = in.nextLine();
		System.out.println("Please enter the passcode of the user" + userName + ".");
		int passcodeFromUser = in.nextInt();
		int passcode = 1234 ;
		if (passcodeFromUser == passcode)
		{
		System.out.println("Hi!" + userName + "!");
		}
		else
		{
			System.out.println("Access denied!");
		}
		
	}
	
}
