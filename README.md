to fufill 1.3.2's tak requirements, I first checked if every digit in the four digit input was correct, and in position by using if statements.

if (g1 == r1)
    {
     correctPositions = correctPositions + 1; 
    }
    if (g2 == r2)
    {
      correctPositions = correctPositions + 1;
    } 
    if (g3 == r3)
    {
      correctPositions = correctPositions + 1;
    } 
    if (g4 == r4) 
    {
      correctPositions = correctPositions + 1;
    } 

I then tell the user how many digits they got correct: 
System.out.println("You have " + correctPositions + " digits in the correct position.");

lastly, I check if they got all 4 digits correct. Else, I tell them that they are wrong. 

if (correctPositions == 4)
    {
      System.out.println("Congrats! You guessed the number!");
    }


OUTPUT:

<img width="1027" height="195" alt="Screenshot 2025-10-19 at 9 00 56 PM" src="https://github.com/user-attachments/assets/9c0145ef-fef6-4c22-9871-f1d308d7a39c" />
    else
    {
      System.out.println("Wrong!");
    }
