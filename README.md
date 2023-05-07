Download Link: https://assignmentchef.com/product/solved-lab-questions-chapter-number-4-loops
<br>
5/5 - (1 vote)

4) You can test to see if an integer, x, is even or odd using the Boolean expression (x / 2) * 2 == x.  Integers that are even make this expression true, and odd integers make the expression false.

Use a for loop to iterate five times.  In each iteration, request an integer from the user.  Print each integer the user types, and whether it is even or odd.  Keep up with the number of even and odd integers the user types, and print “Done” when finished, so the user won’t try to type another integer.  Finally, print out the number of even and odd integers that were entered.

6.1) Use nested for loops to produce the following output

1     1

1     2

1     3

1     4

2     1

2     2

2     3

2     4

Let the outer loop print the numbers in the left column, and the inner loop print the numbers in the right column.  In each iteration, print the loop control variables to produce the output.6.3) Repeat Lab 6.1 using nested do loops.7.1)  Use nested for loops to produce the following output:X

XX

XXX

XXXX

XXXXX

The outer loop can control the number of rows that will be printed.  The inner loop can control the number of X’s that print on a single line.  The trick is to notice that there is a relationship between the row number and the number of X’s in the row.  This relationship allows you to use the outer loop control variable to control the inner loop.7.2) Use nested loops and the code from Lab 2.1 to produce the output below.  The outer loop control variable can be used to help write the inner loop.

The sum of positive integers from 1 to 1 is 1

The sum of positive integers from 1 to 2 is 3

The sum of positive integers from 1 to 3 is 6

The sum of positive integers from 1 to 4 is 10

The sum of positive integers from 1 to 5 is 15…

The sum of positive integers from 1 to 100 is 5050Because we already have a program that computes 1 + 2 + … + n for any positive integer n, we can embed that code in a second loop that loops 100 times.  The outside loop control variable can be used to control the number of times we loop and more importantly, it can be used to control the upper limit of the inner computation.Write the code that will produce the output described above.10.1) A variable that counts the iterations of a loop is called a loop index or loop control variable. In the preceding examples nyear served as an index, counting the number of years to the next millennium. This type of loop is frequently written using a for loop.for (initialization; condition; update){statement}Write a program controlled by two (non-nested) for loops that produces the following listing of inclusive dates, from the fifth century B.C. through the fifth century A.D.Century 5 BC  400-499Century 4 BC  300-399Century 3 BC  200-299Century 2 BC  100-199Century 1 BC  1-99Century 1 AD  1-99Century 2 AD  100-199Century 3 AD  200-299Century 4 AD  300-399Century 5 AD  400-49910.2)  Write the ListCenturies program using a single loop for (i = -5; i &lt;= 5; i++) with an if statement in the body of the loop.11.1) One loop type might be better suited than another to a particular purpose. The following usages are idiomatic:

for   Known number of iterations

while Unknown number of iterations

do    At least one iteration

Convert the following while loop to a do loop.public class PrintSum{public static void main(String[] args){Scanner in = new Scanner(<a href="http://system.in/" target="_blank" rel="nofollow noopener">System.in</a>);int sum = 0;int n = 1;

while (n != 0){System.out.print(“Please enter a number, 0 to quit: “);n = in.nextInt();if (n != 0){sum = sum + n;System.out.println(“Sum = ” + sum);}}}}2)  Convert this while loop to a for loop.

/**Program to compute the first integral power to which 2 can beraised that is greater than that multiple of a given integer.*/public class CountPowerOf2{public static void main(String[] args){Scanner in = new Scanner(<a href="http://system.in/" target="_blank" rel="nofollow noopener">System.in</a>);System.out.print(“Please enter a number, 0 to quit: “);int n = in.nextInt();

int i = 1;while (n * n Math.pow(2, i)){i++;}

System.out.println(“2 raised to ” + i+ ” is the first power of two greater than ” + n + ” squared”);}}}

13)  Convert this for loop to a while loop:

public static void main(String[] args){for (int i = 1; i &lt;= 10; i++){System.out.println(i + ” squared equals ” + i * i);}}

15) To generate random numbers, you construct an object of the Random class, and then apply one of the following methods:nextInt(n): A random integer between the integers 0 (inclusive) and n (exclusive)