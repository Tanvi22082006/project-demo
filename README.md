#include <stdio.h>

int main()
 {
    int score = 0;
    char answer;

    printf("\n//* * * WELCOME TO THE QUIZ APP * * *//\n\n");

    
    printf("\n1.** What is the father of C language?\n");
    printf(" A. Harry\n B. Charles Babbage\n C. Dennis Ritchie\n D. James Gosling\n\n");
    printf("Enter Your Answer: ");
    scanf(" %c", &answer);

    
    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'c' || answer == 'C') 
	{
            score++;
        }

    } 
    else
    {
        
        printf("You are entering wrong alphabet\n");
        printf("Enter Your Answer: ");
    scanf(" %c", &answer);

    
    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'c' || answer == 'C') {
            score++;
        }

    } 
    else
    {
        printf("You are entered wrong option again no more attempts\n");
    }

    }
    
    
    printf("\n2.**Which symbol is used at end of the statement ?\n");
    printf(" A. :\n B. ; \n C. .\n D. ,\n\n");
    printf("Enter Your Answer: ");
    scanf(" %c", &answer);

    
    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'b' || answer == 'B') 
	{
            score++;
        }

    }
     else 
     {
        
        printf("You are entering wrong alphabet\n");
        printf("Enter Your Answer again: ");
    scanf(" %c", &answer);


    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'b' || answer == 'B')
	    {
            score++;
            }

    } 
	else
	 {
        printf("You are entered wrong option again no more attempts\n");
        
     }
   }
     printf("\n3.** What is size of int on most 32-bit system?\n");
    printf(" A. 2-byte\n B. 4-byte\n C. 8-byte\n D. 1-byte\n\n");
    printf("Enter Your Answer: ");
    scanf(" %c", &answer);

    
    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'b' || answer == 'B') {
            score++;
        }

    }
     else 
     {
        
        printf("You are entering wrong alphabet\n");
        printf("Enter Your Answer again: ");
    scanf(" %c", &answer);


    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'b' || answer == 'B') {
            score++;
        }

    } else {
        printf("You are entered wrong option again no more attempts\n");
        
}
    }
     printf("\n4.**Which keyword is used to exit from a loop in C?\n");
    printf(" A. break\n B. stop \n C. exit\n D. end\n\n");
    printf("Enter Your Answer: ");
    scanf(" %c", &answer);

    
    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'A' || answer == 'a') {
            score++;
        }

    }
     else 
     {
        
        printf("You are entering wrong alphabet\n");
        printf("Enter Your Answer again: ");
    scanf(" %c", &answer);


    if (answer == 'a' || answer == 'A' ||
        answer == 'b' || answer == 'B' ||
        answer == 'c' || answer == 'C' ||
        answer == 'd' || answer == 'D') {
        
        if (answer == 'A' || answer == 'a') {
            score++;
        }

    } else {
        printf("You are entered wrong option again no more attempts\n");
        
}
    }



    printf("\n \\* * * The Quiz is Completed * * *\\ \n");
    printf("Your total correct answers: %d out of 4\n", score);
    printf("    || Thank you!  ||   ");
return 0;
}
