add-a-constructor
=================

random number with constructor



import java.util.Scanner;

public class NumberGuessing {
	
public static void main (String[] args) {

int count = 1; 
int computerNum;

do{

System.out.println("Count is:" +count); count++;
computerNum = 0 + (int) (Math.random() * 3);

System.out.println(" Secret number is " + computerNum);
Scanner keyboard = 
new Scanner ( System.in);

int guess;

System.out.print ( " Enter a guess: ");

guess = keyboard.nextInt ();
System.out.println ( " Your guess is " + guess);

 if (guess == computerNum)

System.out.println ( " Your guess is correct. Congradulations!");

else if ( guess < computerNum)

System.out.println ( " Your Guess is smaller than the secret number.");

else if ( guess > computerNum)

System.out.println ( " Your guess is greater than the secret number.");

}
while (count<9999999*9999999); 
}

public int NumberGuessing;

public NumberGuessing()
{
	NumberGuessing=1+(int)(Math.random() *3);
}

public int computerNum()
{
	return NumberGuessing;
}

} 
