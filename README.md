# MODULE-4
# Program-4-a
## C-Module 4
## EX_NO-04)a)-Datatypes & Operators
### Date: 19-10-2025
### Name: SYEAD JASLIN S
### Register Number:25017223
## AIM:
Write a C Program to perform bitwise OR operation of  12 and 15 integers. 
## ALGORITHM:
1. Start the program.
2. Declare two integer variables a and b, and initialize them with 12 and 15 respectively.
3. Perform a bitwise OR operation on a and b using the '|' operator.
4. Print the result of the bitwise OR operation using printf.
5. End the program.
## PROGRAM:
```
#include<stdio.h>
int main()
{
    int a=12,b=15;
    printf("Bitwise-OR result is = %d",a|b);
    return 0;
}
```
## OUTPUT:
<img width="835" height="245" alt="Screenshot 2025-10-19 223747" src="https://github.com/user-attachments/assets/90723adf-ac7f-4952-b6f5-a33ba1ee82fa" />

## RESULT:
Thus the program to perform bitwise OR operation of  12 and 15 integers has been executed successfully
# Program-4-b
## C-Module 4
## EX_NO-04)b)-Unconditional Statements
### Date: 19-10-2025
### Name: SYEAD JASLIN S
### Register Number:25017223
## AIM:
Input the three angles of Triangle from the user and check whether a triangle can be formed by the given value for the angles using if-else
## ALGORITHM:
1. Start the program.
2. Declare three integer variables to store the angles of a triangle.
3. Read the three angle values from the user using scanf.
4. Check if the sum of the three angles is equal to 180:

    a. If true, print "The triangle is valid."

    b. If false, print "The triangle is not valid."

5. End the program.

## PROGRAM:
```
#include<stdio.h>
int main()
{
    int ang1,ang2,ang3;
    scanf("%d\n%d\n%d",&ang1,&ang2,&ang3);
    if(ang1+ang2+ang3==180)
    printf("The triangle is valid.");
    else
    printf("The triangle is not valid.");
}
```
## OUTPUT:
<img width="842" height="481" alt="Screenshot 2025-10-19 224218" src="https://github.com/user-attachments/assets/81ed965e-f5e0-4d72-bfc9-8aea636b5c82" />

## RESULT:
Thus the program to check whether a triangle can be formed by the given value for the angles using if-else has been executed successfully
# Program-4-c
## C-Module 4
## EX_NO-04)c)-Strings
### Date: 19-10-2025
### Name: SYEAD JASLIN S
### Register Number:25017223
## AIM:
write a Program to compare two strings using strcmp().
## ALGORITHM:
1. Start the program.
2. Declare two character arrays to store the input strings.
3. Read the first string from the user using fgets.
4. Read the second string from the user using fgets.
5. Compare the two strings using strcmp and store the result in a variable.
6. Check the result of strcmp:
 
    a. If it is 0, print "strings are same".

   b. Otherwise, print "strings are not same".

7. End the program.

## PROGRAM:
```
#include<stdio.h>
#include<string.h>
#include<stdio.h>
int main()
{
    char word1[20],word2[20];
    fgets(word1,sizeof(word1),stdin);
    fgets(word2,sizeof(word2),stdin);
    int comp=strcmp(word1,word2);
    if(comp==0)
    printf("strings are same");
    else
    printf("strings are not same");
}
```
## OUTPUT:
<img width="836" height="284" alt="Screenshot 2025-10-19 224720" src="https://github.com/user-attachments/assets/0cf18f8b-69ef-4372-bd67-44665f0c56e0" />

## RESULT:
Thus the program to compare two strings using strcmp() has been executed successfully
# Program-4-d
## C-Module 4
## EX_NO-04)d)-STRINGS
### Date: 19-10-2025
### Name: SYEAD JASLIN S
### Register Number:25017223
## AIM:
Write a C program to count the total number of words in a given string using While loop.
## ALGORITHM:
1. Start the program.
2. Declare a character array to store the input string and an integer variable space initialized to 0.
3. Read a line of text from the user using scanf("%[^\n]", word).
4. Use a for loop to iterate through each character of the string:

     a. If the character is a space (' '), increment the space counter.

5. After the loop, print the total number of words by adding 1 to the space counter.
6. End the program.

## PROGRAM:
```
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    char word[100];
    int space=0;
    scanf("%[^\n]",word);
    for(int i=0;i<strlen(word);i++)
    {
       if(word[i]==' ')
       space++;
    }
    printf("%d",space+1);
}
```
## OUTPUT:
<img width="852" height="232" alt="Screenshot 2025-10-19 225056" src="https://github.com/user-attachments/assets/2da98427-cb4b-49fd-b063-98751bcccd32" />

## RESULT:
Thus the program to count the total number of words in a given string using While loop has been executed successfully
# Program-4-e
## C-Module 4
## EX_NO-04)e)-STRINGS
### Date: 19-10-2025
### Name: SYEAD JASLIN S
### Register Number:25017223
## AIM:
Write a C program to find vowels in a given string using function
## ALGORITHM:
1. Start the program.
2. Declare a character array to store the input string and an integer variable vol initialized to 0.
3. Read a line of text from the user using scanf("%[^\n]", word).
4. Use a for loop to iterate through each character of the string:

    a. If the character is a vowel (a, e, i, o, u in both uppercase and lowercase), increment the vol counter.

5. After the loop, print the total number of vowels stored in vol.
6. End the program.
## PROGRAM:
```
#include<stdio.h>
#include<string.h>
#include<ctype.h>
int main()
{
    char word[100];
    scanf("%[^\n]",word);
    int vol=0;
    for(int i=0;i<strlen(word);i++)
    {
        if(word[i]=='a'||word[i]=='A'||word[i]=='e'||word[i]=='E'||word[i]=='i'||word[i]=='I'||word[i]=='o'||word[i]=='O'||word[i]=='u'||word[i]=='U')
        vol++;
        
    }
    printf("%d",vol);
}
```
## OUTPUT:
<img width="833" height="233" alt="Screenshot 2025-10-19 225404" src="https://github.com/user-attachments/assets/eed78bc8-1237-4d2e-996d-c98982106f6e" />

## RESULT:
Thus the program to find vowels in a given string using function has been executed successfully
