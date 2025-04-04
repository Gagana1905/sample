# sample
#include <stdio.h>

int main() {
    char name[50];

    printf("Hello! What's your name? ");
    scanf("%s", name);  // Reads user input

    printf("Nice to meet you, %s!\n", name);
    
    return 0;
}
