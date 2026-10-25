Tutorial 03 - Answers

Question 1

a) if (3*8==27)
  
   {
    System.out.println("True");
   }

   else
   {
    System.out.println("False");
   }

b) if ( x %2 == 0)
   {
    System.out.println("Even Number");
   }
    
   else
   {
    System.out.println{(Odd Number");
   }

c) if (ch >= 'A' && ch <= 'Z')

    {
    System.out.println("Capital Letter");
    }

    else
    {
    System.out.println("Not a Capital Letter");
    }

d)  if (str1.compareToIgnoreCase(str2) < 0)
    (
     System.out.println(str1);
     System.out.println(str2);   
    )

    else
    (
        System.out.println(str2);
        System.out.println(str1);
    )

e)  switch(day)
    {
        case 0:
        System.out.println("Sunday");
        break;

        case 1 : 
        System.out.println("Monday");
        break;

        case 2 :
        System.out.println("Tuesday");
        break;

        case 3:
        System.out.println("Wedenesday");
        break;

        case 4:
        System.out.println("Thursday");
        break;

        case 5:
        System.out.println("Friday");
        break;

        case 6;
        System.out.println("Saturday");
        break;
    }

Question 2

a)  if (num1 == num2) 
    System.out.println("Number 1 is equal to number 2.");

b)  if (x > y && x > z)      
    System.out.println("x is the largest number");

c)  String s1 ="Java", s2= "java"; 
    if (s1.equals(s2)) 
    System.out.println("They are equal strings."); 
    else  
    System.out.println("They are not equal strings.");

e)  if (x>0 || y>0)
    System.out.println("Either x or y is positive");

Question 3 

when x = 9 and y = 10

a)  if (x < 10)                   
    if (y > 10) 
    System.out.println("*****"); 
    else 
    System.out.println("#####"); 
    System.out.println("$$$$$");

Output : #####
         $$$$$

b) if (x < 10)
     { 
    if (y < 10)  
    System.out.println("*****"); 
    else{ 
    System.out.println("#####"); 
    System.out.println("$$$$$");  
    }
    } 

Output :  #####
          $$$$$

c)  if (x < 10) { 
    if (y < 10) 
    System.out.println("*****"); 
    System.out.println("#####"); 
    } 
    else { 
    System.out.println("$$$$$");  
    } 

Ouput: #####4

d)  if (x > 10) { 
    if (y > 10) { 
    System.out.println("*****"); 
    System.out.println("#####"); } 
    else  
    System.out.println("$$$$$"); 
    }

Output :                            // No output

Question 4 

int a = 30 , b = 20, c = 10;

if (a>b && a>c)
{
    System.out.println("a is the biggest number");
}
else if (b>a && b>c)
{
    System.out.println("b is the biggest number);
}
else
{
    System.out.println("c is the biggest number");
}

Question 5

int year = 2026;

if ((year %4 == 0 && year %100 != 0 ) || (year %400 == 0))
{
    System.out.println(year + "is a leap year");
}
else
{
    System.out.println(year + "is not a leap year");
}