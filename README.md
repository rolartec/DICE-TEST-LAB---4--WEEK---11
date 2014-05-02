DICE-TEST-LAB---4--WEEK---11
============================

"DICE TEST- LAB # 4 WEEK 11

//  BY REINA OLARTE

//  "DICE TEST"  LAB#  4  WEEK  #  11

import java.util.Scanner;

public class DiceTest 
{
	public static void main( String[]args)	
	{
	Scanner input = new Scanner(System.in);
	
//  VARIABLES:
	
	String Answer;
	
	int CompNumber;
	
	boolean SIGA = true;
	
		while(SIGA)
		{
			CompNumber = Dice.oneThrow();
			
		System.out.printf("Generated Number after one roll is: %d\n\n", CompNumber);
		
		System.out.println("Do you want to continue playing?:  Yes = Y, No  = N Please");
		
		Answer = input.next();
		
		if (Answer.toUpperCase().startsWith("N"))
			
		{
			SIGA = false;
		}
		}
	}
}
