#include"declaration.h"
#include"welcome.h"
#include"menu.h"
#inlcude"newscoresheet.h"
#include"filling.h"
#include"final.h"
int main()
{
   system("color f1");
   int a,key;
   char b,ch;
   FILE *fnew;
   
   char lastinput;
   while (TRUE)
   {
      intializeconsolehandles();
      welcome();
      system("cls");
      menu();
      locate(32,9);
      ch=getch();
      switch(ch)
      {
           case '1':
           fileopen(ch);
           case '2':
           fileopen(ch);
           case '3':
           system("cls");
           exit(0);
       }
    }
 }   
           
