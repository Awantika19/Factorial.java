# Factorial.java
com.java.basics

package com.java.basics;

public class Factorial {

	public static void main(String[] args) {
		 int num = 15;
		 
		 
		 if (num < 0) {
			 System.out.println("Invalid number for factorial as -ve numbers dont have factorials");
			 
		 }else if(num == 0) {
			 System.out.println("FACTORIAl = 1");
		 }else {
			 int ans = 1;
			 for (int i = num; i >= 1; i--) {
				 ans *= i;
				 ans = ans * i;
			 }
			 System.out.println("FACTORIAL ==> " + ans);
		 }
	}

}
