//# TirePressure2
//A Code that checks the tire pressure of all 4 tires
//By Jared Yancey
import java.util.Scanner;

public class Program {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner(System.in);
		
    //front left
		int tirepressure;
		
    //front right
    int tirepressure2;
    
    //back left
		int tirepressure3;
		
    //back right
    int tirepressure4;
		
    //Front Left
			System.out.println("Enter Tire Pressures");
			
			System.out.println();
			
		System.out.println("Front Left:");
		
    tirepressure = sc.nextInt();
		
    System.out.println("-----Checking-----");
		
    //Flow to see what the tire pressure is at
		if(tirepressure < 25 && tirepressure > 0) {
    System.out.println("Your tire pressure is low.");
    }
		else if(tirepressure <= 0) {
    System.out.println("Either you have a flat, or your messing with the code by putting a negative number.");
    }
		else if(tirepressure > 44) {
    System.out.println("You know it cant be higher than 44 right? Stop messing with the code and be serious.");
    }
		else {
			if(tirepressure < 27) {
    System.out.println("Your tire pressure is close to being bad but for now its fine.");	
    }else {
				System.out.println("Your tire pressure is good.");
			}
			}
		System.out.println();
		
    //Front Right
    System.out.println("Front Right:");
    tirepressure2 = sc.nextInt();
			System.out.println("-----Checking-----");
      
		 //Flow to see what the tire pressure is at
		if(tirepressure2 < 25 && tirepressure2 > 0) {
			System.out.println("Your tire pressure is low.");
		}
		else if(tirepressure2 <= 0) {
			System.out.println("Either you have a flat, or your messing with the code by putting a negative number.");
		}
		else if(tirepressure2 > 44) {
			System.out.println("You know it cant be higher than 44 right? Stop messing with the code and be serious.");
		}
		else {
			if(tirepressure2 < 27) {
			System.out.println("Your tire pressure is close to being bad but for now its fine.");	
			}else {
				System.out.println("Your tire pressure is good.");
			}
			}
		System.out.println();
    
    //Back Left
		System.out.println("Back Left:");
    
		tirepressure3 = sc.nextInt();
    
			System.out.println("-----Checking-----");
		
     //Flow to see what the tire pressure is at
		if(tirepressure3 < 25 && tirepressure3 > 0) {
			System.out.println("Your tire pressure is low.");
		}
		else if(tirepressure3 <= 0) {
			System.out.println("Either you have a flat, or your messing with the code by putting a negative number.");
		}
		else if(tirepressure3 > 44) {
			System.out.println("You know it cant be higher than 44 right? Stop messing with the code and be serious.");
		}
		else {
			if(tirepressure3 < 27) {
			System.out.println("Your tire pressure is close to being bad but for now its fine.");	
			}else {
				System.out.println("Your tire pressure is good.");
			}
			}
		System.out.println();
    
    //Back Right
		System.out.println("Back Right:");
		tirepressure4 = sc.nextInt();
			System.out.println("-----Checking-----");
		
     //Flow to see what the tire pressure is at
		if(tirepressure4 < 25 && tirepressure4 > 0) {
			System.out.println("Your tire pressure is low.");
		}
		else if(tirepressure4 <= 0) {
			System.out.println("Either you have a flat, or your messing with the code by putting a negative number.");
		}
		else if(tirepressure4 > 44) {
			System.out.println("You know it cant be higher than 44 right? Stop messing with the code and be serious.");
		}
		else {
			if(tirepressure4 < 27) {
			System.out.println("Your tire pressure is close to being bad but for now its fine.");	
			}else {
				System.out.println("Your tire pressure is good.");
			}
			}
	}
}
