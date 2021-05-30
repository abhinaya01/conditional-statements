#include<stdio.h>

int main()
  
  {
  	  float marks1,marks2,marks3,marks4,marks5,average;
  	  
  	  
  	  printf("Enter marks obtained in subject 1:");
  	  scanf("%f",&marks1);
  	  
  	  printf("Enter marks obtained in subject 2:");
  	   scanf("%f",&marks2);
  	   
  	   printf("Enter marks obtained in subject 3:");
  	   scanf("%f",&marks3);
  	   
  	   
  	   printf("Enter marks obtained in subject 4:");
  	   scanf("%f",&marks4);
  	   
  	   
  	   printf("Enter marks obtained in subject 5:");
  	   scanf("%f",&marks5);
  	   
  	   average=(marks1+marks2+marks3+marks4+marks5)/5;
  	   
  	   printf("average:%0.2f\n",average);
  	   
  	   if (average>=85 && average<=100)
  	      {
  	      	printf("Grade A");
  	      }
  	      
  	      else if (average>=70 && average<=84)
			{
				printf("Grade B");
			 } 
			 
			  else if (average>=55 && average<=69)
			{
				printf("Grade C");
			 } 
			 else if (average>=40 && average<=54)
			{
				printf("Grade D");
			 } 
			 else 
			{
				printf("Grade F");
			 } 
			 return 0;
		}
