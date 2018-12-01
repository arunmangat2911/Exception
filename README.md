# Exception

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */

/**
 *
 * @author NetworkAcademy
 */

import java.util.Scanner;

public class Exception1 {
    
    public static void main(String[] args) {
        
        try 
        {
        Scanner input = new Scanner(System.in);
        System.out.println("Enter number 1: ");
        int number1 = input.nextInt();
        System.out.println("Enter number 2: ");
        int number2 = input.nextInt();
        
        int result = number1/number2;
        System.out.println("Result is : " + result);
        }
        catch(Exception E)
        {
            System.out.println("Undefined number");
            
        }
             
    }
    
}
