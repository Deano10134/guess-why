//program to check if a string is a palindrome or not
#include<iostream.h>
#include<stdio.h>
#include<string.h>
#include<conio.h>
void main()
{  clrscr();
char mo[100]; int t, flag=1;
cout<<"Enter the string\n";
cin.getline(mo,100);
t=strlen(mo); int i, j;
cout<<"The original string is\n";
for(i=0;i<t;i++)
{cout<<mo[i];
}  int temp;cout<<endl;
cout<<"For the reverse string\n";
for(j=t;j>=0;j--)
{cout<<mo[j];
 }
    cout<<endl;
for(i=0,j=t-1;i<t/2;i++,j--)
{
 if(mo[i]!=mo[j])
 {flag=0;
  break;
  } }
if(flag==1)
 cout<<"Palindrome";
else
 cout<<"not a palindrome";
 char a[50],b[50], c[50];
 cout<<"Enter string 1";
 gets(a);
 cout<<"Entertstring 2";
 gets(b);
 strcat(a,b);
 cout<<a;
 getch();
 }
