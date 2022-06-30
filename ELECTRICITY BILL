#include<stdio.h>
#include<conio.h>
struct Bill{
char firstName[100];
char lastName[100];
char Address[200];
float previousUnit;
float presentUnit;
};
float generateBill(struct Bill temp)
{
float diff;
diff = temp.presentUnit - temp.previousUnit;
if(diff > 20){
return diff*4.75;
}
else{
return 20*4.75+(diff-20)*7.75;
}
}
void main(){
struct Bill bill; /*Declaration of structure variable*/
{printf("Fill up the following: \n");
printf("First Name: ");
scanf("%s",bill.firstName); 
printf("Last Name: ");
scanf("%s",bill.lastName);
printf("\nAddress: ");
scanf("%s",bill.Address);
printf("Previous Unit: ");
scanf("%f",&bill.previousUnit);
printf("Present Unit: ");
scanf("%f",&bill.presentUnit);
printf("\a\n\n********ElectricityBill***********\n\n\a");
printf("Name: %s %s",bill.firstName,bill.lastName);
printf("\nAddress: %s",bill.Address);
printf("\nPrevious Unit: %.3f       Current Unit: %.3f",bill.previousUnit,bill.presentUnit);
printf("\nCost: %.3f\n\n",generateBill(bill));
getch();}
}
