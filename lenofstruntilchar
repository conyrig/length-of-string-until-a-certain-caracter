// Unfinished

#include <stdio.h>
#include <string.h>

int whatsTheLenght(char *string){
    int i=0;
    char stringToLookFor[]="OF";
    
    for(i=0;i<strlen(string);i++){
        if(string[i]==stringToLookFor[i] && string[i+1]==stringToLookFor[i+1]){
            printf("%s was found. The string lenght is %d caracters\n", stringToLookFor, i);
            return i;
        }
        else if(string[i]=='\0' && string[i]!=stringToLookFor[i] && string[i+1]!=stringToLookFor[i+1]){
            printf("%s was not found!\n", stringToLookFor);
            return -1;
        }
    }
}

int main(){
    char string[]="EXAMPLE OF STRING";
    
    whatsTheLenght(string);
    
    return 0;
}
