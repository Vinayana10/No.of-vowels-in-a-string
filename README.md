# No.of-vowels-in-a-string

#include <stdio.h>
#include <string.h>
int cvow(char str[]){
    int count=0,i,n;
    n=strlen(str);
    for(i=0;i<n;i++)
    {
        if(str[i]=='a' || str[i]=='e' || str[i]=='i' || str[i]=='o' || str[i]=='u' || str[i]=='A' ||str[i]=='E' ||str[i]=='I' || str[i]=='O' || str[i]=='U'){
            count++;
        } 
    } return count;
}

int main()
{
  
char str[200];
printf("Enter a name:");
scanf("%s",str);
printf("\nYour Name: %s",str);

printf("Number of vowels in given name: %d\t",cvow(str));
    return 0;
}
