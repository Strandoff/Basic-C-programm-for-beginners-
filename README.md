#include <stdio.h>

int main()
{
    // Variable for character is"'any"
    char any[1];
    //Variable for integer is "a"
    int a;

    printf("Hi! My name is computer\n");

    printf("Enter your name:(But Remember, not you FuLl nAmE)\n ");

    scanf("%s", any);

    printf("Nice name!");

    printf("\nEnter your favorite number:\n");

    scanf("%d", &a);

    printf("Hey! Even I like that number");

    printf("\n Your name is: %s", any );

    printf ("\n Your favorite number is: %d", a );

    return 0;
}
