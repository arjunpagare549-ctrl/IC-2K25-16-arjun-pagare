/*Q1 how to input data from user for creating an array
#include <stdio.h>
int main(){
    int arr[5];
    printf("enter the 5 elements of your array : ");
    for(int i=0; i<5; i++){
        scanf("%d",&arr[i]);
}
printf("the 5 element of you array are : \n");
for(int i=0; i<5; i++){
    printf("%d ", arr[i]);
}
return 0;
