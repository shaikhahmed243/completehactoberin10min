#include <stdio.h>
#include <conio.h>

void main()
{
    int x = 2;
    clrscr();
    
    switch(x) {
        case 2:
            printf("Two\n");
        case 3:
            printf("Three\n");
    }
    
    getch();
}
