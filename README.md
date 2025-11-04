# -APP-REVIEW-EELTUT2
    #include<stdio.h>
int main(){

    char grade[10];
    printf("WELCOME TO THE APP REVIEW GRADER\n");
    printf("Please answer the following questions on a scale of 1 to 5, where 5 is excellent and 1 is poor.\n\n");
    float rating1,rating2,rating3,rating4,rating5;
   
    printf("How satisfied are you with the app's performance (speed and responsiveness)?\n");
    scanf("%f",&rating1);
   printf(" How well does the app handle errors or issues when they arise?\n");
   scanf("%f",&rating2);
    printf("How satisfied are you with the frequency and quality of updates or new features?\n");
    scanf("%f", &rating3);
    printf("How likely are you to recommend this app to your family and friends?\n");
     scanf("%f",&rating4);
     printf("Overall, how satisfied are you with your experience using this app?\n");
     scanf("%f",&rating5);
     
     float avg=(rating1+rating2+rating3+rating4+rating5) /5;
     printf("\nAPP REVIEW SUMMARY\n");    
     printf("AVERAGE POINTS=%f\n",avg);
     if(avg>=4.5){
   printf("GRADE=A");}
     else if(avg>=3.5 &&avg<4.5){
     printf("GRADE=B");}
    else if(avg>=2.5 &&avg<3.5){
    printf("GRADE=C");}
      else if(avg>=1.5 && avg<2.5){
               printf("GRADE=D");}
              else{
                   printf("GRADE=F");
              }
    return 0;
} 
