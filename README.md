# Cricket-scoresheet
program
#include<stdio.h>
#include<dos.h>
#include<windows.h>
#include<winbase.h>
#include<conio.h>
#include<time.h>
#include<string.h>
#include”declaration.h”
#include”welcome.h”
#include”menu.h”
void scoresheet()
   struct css
   {
      int runs,wickets;
      char nmb[20],numb[20];      //nmb: name of batsman,numb: name of bowlers//
      int overs,extrs;
      float ecb;strkrt;            //ecb:economy of bowler//
      int nbb,frs,sixs;            //nbb:no balls,frs:number of fours,sixs:no of six's//
   }
int main(0
{
   file=*fp;
   fp=fopen("struct css c[20]");
   return 0;
}
void scoresheet()
{
  struct css c[20]
  int i;
  printf("Enter Runs Wickets Overs Extras");
  printf("enter  economy strike rate");
  printf("enter  no of balls fours sixs");
  for(i=0;i<20;i++)
  {
     scanf("%d   %d  %d  %d",&runs,&wickets,&overs,&extrs);
     scanf("%f     %f   %d   %d   %d",&ecb,&strktr,&nbb &frs,&sixs);
     gets(nmb);
     gets(numb);
  } 
    for(i=0;i<20;i++)
  {
     printff("%d   %d  %d  %d",runs,wickets,overs,extrs);
     printf("%s    %s ",nmb,numb);
    printf("%f     %f   %d   %d   %d",ecb,strktr,nbb frs,sixs);
  } 
    
}
     
