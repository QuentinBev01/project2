# project2
bubbles and pointers 
#include <stdio.h>
const int MAX=9;

void printValues(int*);
void sort(int*);
void swap(int*, int*);

int main(){
  int values[] = {7, 3, 9, 4, 6, 1, 2, 8, 5};
  printf("Before: \n");
  printValues(values);

  // test swap
  int x = 3;
  int y = 5;
  printf("x: %d, y: %d \n", x, y);
  swap(&x, &y);
  printf("x: %d, y: %d \n", x, y);

  sort(values);
  printf("After: \n");
  printValues(values);

  return(0);
} // end main

##main
produce an array of integers
print the array
create the temporary ints
test the swap funciton 
Run the sort function on the arrays
print the sorted array

##printvalues
takes an int pointer representing the array
step through the array with a loop 
print each member of the array 
print a newline at the end
return void

