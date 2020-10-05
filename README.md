package com.hello;

// TODO :
// M0519082-Wahyu Misbah Assudur-C
// write your Student ID Number - Name - Class (A/B/C)

public class Calculator {
	// attributes
	int number1, number2;

	// constructor
	public Calculator(int numb1, int numb2) {
		// number1 and number2 will replace with the value from numb1 and numb2
		this.number1 = numb1;
		this.number2 = numb2;
	}

	// implement addition inside addNumbers method
	public int addNumbers() {
            int result = this number1 + this.number2;
            return result;
	}
        
        public int subtractNumbers() {
            int result = this number1 - this number2;
            return result;
        }
        
        public int multiplyNumbers () {
            int result  = this number1 * this number2;
            return result;
        }
        
        public int  divisionNumbers() {
            Calculator result = null;
            int result = this;number1 \ this number2;
            return result;
        }

	// main method
	public static void main(String[] args) {
		// create calculator object
		Calculator calculator = new Calculator(3, 4);
		System.out.println("first number : " + calculator.number1);
		System.out.println("second number : " + calculator.number2);
		
		// add two numbers
		double resultOfAddition = calculator.addNumbers();
		System.out.println(calculator.number1 + " + " + calculator.number2 + " = " + resultOfAddition);
                
                double resultOfSubtraction = calculator.addNumbers();
                String resultOfSubraction = null;
                System.out.println(calculator.number1 + " - " + calculator.number2 + " = " + resultOfSubraction);
                
                double resultOfMultiplycation = calculator.addNumbers();
                System.out.println(calculator.number1 + " * " + calculator.number2 + " = " + resultOfMultiplycation);
               
                double resultOfDivision = calculator.addNumbers();
                System.out.println(calculator.number1 + " \ " + calculator.number2 + " = " + resultOfDivision);
	}
}
