# BAsic7

Pattern number Stars

Take as input N, a number. Print the pattern as given in the input and output section.


Input Format

Enter value of N

Constraints

1 <= N < 10

Output Format

Print the pattern.

Sample Input

7

Sample Output

1******

12*****

123****

1234***

12345**

123456*

1234567

Explanation

There is no space between any two numbers. Catch the pattern for corresponding input and print them accordingly.



solution



import java.util.*;

public class Main {

public static void main(String args[]) {

Scanner sc = new Scanner(System.in);

int n = sc.nextInt();

int ndt = 1;

int nst = n-1;

// row

int row = 1;

while(row <= n){

// work

int cdt = 1;

while(cdt <= ndt){

System.out.print(cdt);

cdt++;

}

int cst = 1;

while(cst <= nst){

System.out.print("*");

cst++;



}

//preparation

System.out.println();

ndt = ndt + 1;

nst = nst - 1;

row = row + 1;

}


    }

}
