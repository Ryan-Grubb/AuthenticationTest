# AuthenticationTest

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package Looping;
import java.util.Scanner;
/**
 *
 * @author ryan.grubb
 */
public class LoopSandbox {
    public static void main(String[] javaRocks){
       int numAttempts = 0;
       int numAllowedAttempts = 3;
       final String Correct_UserName = "javaghost";
       final String Correct_PassWord = "ic0d3";
       
       String enteredUsername;
       String enteredPassword;
       Scanner userInputScanner = new Scanner(System.in);
       
        
        
        while(numAttempts < numAllowedAttempts){
        System.out.println("Enter your username followed by enter: ");
        enteredUsername = userInputScanner.next();
        
        System.out.println("Enter your password followed by enter: ");
        enteredPassword = userInputScanner.next();
        
            if(enteredUsername.equals(Correct_UserName) && enteredPassword.equals(Correct_PassWord)){
            System.out.println("Authentication Successful! You have logged into Nothing!");
            break;
        
            } else {
            numAttempts = numAttempts + 1;
            System.out.println("Failure to Authenticate! This attempt will be recorded. "
                    + "Number of attemps: " + numAttempts + " Number of allowed Attempts: " + numAllowedAttempts + " Please try again: ");
            
            
            }
        }
        if(numAttempts == 3){
            System.out.println("You have used all of your attempts, DELETING ALL DATA!");
        }
    }
}
