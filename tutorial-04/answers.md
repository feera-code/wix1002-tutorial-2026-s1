Tutorial 04 - Answers 

Question 1 

a)  int n = 1;

    while ( (n*n*n) < 2000 )
   {
    n++;
   }

   n--;

b) for ( int i = 1, i <= 12;  i ++)

   (
    System.out.println(i*i);
   )

c)  for (int i = 1; i<=4 ; i++ )
        {

        for ( int j = 1; j<=5; j++)

        {
        int num = gen.nextInt(101);
        System.out.print(num + " ");
        }

        System.out.println();

        }

d)   System.out.print( "Enter a number: " );
     int num = read.nextInt();
     int sum = 0;

     for ( int i = 1 ; i <= num; i++ )
     {
        sum += i; 
         if ( i < num)
         {
             System.out.print( i + "+");
         }
         else
         {
             System.out.print(i);
         }
     }
        System.out.print("= " + sum);

e) double sum = 0;
     for ( double i = 1 ,j = 25; i<=25 && j >= 1; i++, j--)   
    {    
          if ( i < 25 ) 
           {
            sum += (double)(i) / j;
            System.out.print(i + "/" + j + "+");
           }
            else 
           {
            sum += (double)(i) / j;
            System.out.print(i + "/" + j);
           }

    }   
         System.out.printf(" = %.2f " , sum);
        
    
Question 2 

a)  int sum = 0;
    for ( x = 10; x > 0 ; x--)
    sum += x;

b)  do 
    {
        int x +=2;
        int y +=x;
        System.out.println( x + "and" + y);
        
    }while ( x < 100 );


c)  for ( int x=1,y=2 ; x < y ; x++,y -=2 )
    {
        System.out.println(x + " " + y);
    }

d)  int i = 1;
    while (i<10)
    {
        i++;
    }
    System.out.println("Program End");

Question 3

int first = 1, second = 1, next;

System.out.print(first + " " + second + " ");

for ( int i = 3 ; i <= 10; i++)
{
    next = first + second;
    first = second;
    second = next;
    System.out.print(next + " ");

}

Question 4 

import java.util.Scanner;
Scanner read = new Scanner(System.in);

String word = read.next();

for (int  i = word.length() - 1 ; i >= 0  ; i-- )
{
    char letter = word.charAt(i);
    System.out.print(letter);
}