#include <stdio.h>
#include<math.h>

int main(){
  
  int Number, square, rem, Sum;
  
  printf("Enter Number to Check = ");
  scanf("%d", &Number); //scans for the number
  printf("%d", Number);

  square = pow(Number, 2);

  for (Sum = 0; square > 0; square = square / 10){
    rem = square % 10;
    Sum = Sum + rem; //the calculations
  }

  if (Number == Sum){ //prints out the answer
    printf("\n%d is a Neon Number.\n", Number);
  }else{
    printf("\n%d is not a Neon Number.\n", Number);
  }
  printf("\nThanks for visiting, have a nice day :)");
}
