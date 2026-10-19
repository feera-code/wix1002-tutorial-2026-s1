1. Tutorial 02 - answers

Question 1 

a) System.out.print("Faculty of Computer Science ");
   System.out.println("and Information Technology ");
  

b) System.out.println("Faculty\nof Computer\nScience and\nInformation Technology.");

Question 2

a) System.out.println("SDN");

Question 3

a) System.out.println("Java Programming");
b) System.out.println("Introduction to Java");
c) System.out.println("\t is the horizontal tab character");
d) System.out.println("IJava is cave sensitive!");

Question 4

a) int matrixnum;
b) double pi;
c) boolean M = false;
d) double P = 8800000000;
e) char letter = 'U';
f) final String PRO = "Java";

Question 5

a) final double AMOUNT = 32.5;
   AMOUNT += 10;
   System.out.println("The amount is " + AMOUNT);

b) String chapter= "Summary";
   System.out.println(chapter);

c) int num;
   ++num;
   int num1=num;   

d) double num = 3000;
   System.out.printf("%4.2f\n", num);

e) String contact;
   Scanner keyboard = new Scanner(System.in);
   contact= keyboard.nextLine();   

Question 6

import java.util.Scanner;

public class CircleCircumference {
    public static void main(String[] args) {
    Scanner read = new Scanner(System.in);

System.out.print("Enter diameter: ");
double diameter = read.nextDouble();

double circumference = Math.PI*diameter;

System.out.printf("The circumference of the circle is : %.3f\n", circumference);

 }

}

Question 7 

import java.util.Scanner;

public class inchestometers {
    public static void main(String[] args) {
    Scanner read = new Scanner(System.in);

System.out.print("Enter value in inch: ");
double inch = read.nextDouble();

double convert = inch*0.0254;

System.out.printf("%.2f inches =  %.2f meters", inch, convert );

 }

}
