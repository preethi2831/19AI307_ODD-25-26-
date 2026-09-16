# Ex.No:1(B) CONDITIONAL STATEMENT

## QUESTION:
A pirate ship has a code lock that only opens if:

1)The input code is even, and

2)If it is less than 100, say "Weak Code".

3)If it is between 100 and 999, say "Strong Code".

4)If the code is odd, deny access.

## AIM:
To write a Java program that accepts a code number and determines the security level based on the given conditions:

If the code is even and less than 100 → Display "Weak Code"
If the code is even and between 100 and 999 → Display "Strong Code"
Otherwise → Display "Access Denied"

## ALGORITHM :
Start the program.
Create a Scanner object to read input from the user.
Read an integer value from the user and store it in variable 'code'. - Print "Strong Code". c. Else: - Print "Access Denied".
If 'code' is odd:
Print "Access Denied".
End the program.

## PROGRAM:
/*
Program to implement a conditional statement using Java

Developed by: N Preethika

RegisterNumber: 212223040130
*/
## SOURCE CODE:
import java.util.Scanner;

public class PirateCodeLock {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int code = sc.nextInt();

        if (code % 2 == 0) {
            if (code < 100) {
                System.out.println("Weak Code");
            } else if (code >= 100 && code <= 999) {
                System.out.println("Strong Code");
            }
            else
            {
                System.out.println("Access Denied");
            }
        } else {
            System.out.println("Access Denied");
        }
    }
}

## OUTPUT:

<img width="1253" height="395" alt="image" src="https://github.com/user-attachments/assets/567eeca1-1e3b-489e-83af-41b4baa36db5" />

## RESULT:
Therefore,the program has been executed successfully.
