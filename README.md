# Student_Marks
package com.javaAssigment;

import java.util.Scanner;

public class StudentMarks {

	public static void main(String[] args) {
		Scanner Mark = new Scanner(System.in);
		System.out.println("Enter The Marks");
		int Marks = Mark.nextInt();
		if(Marks<35) {
			System.out.println("Student failed");
		}else if(Marks==35) {
			System.out.println("Student is Just Passed");
		}else if(Marks>35 && Marks<75) {
			System.out.println("Student is  Thrid class");
		}else if(Marks>=75 && Marks<85) {
			System.out.println("Student is Second class");
		}else {
			System.out.println("Student is First class");
		}Mark.close();

	}

}
