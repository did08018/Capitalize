#include <cs50.h>
#include <string.h>
#include <stdio.h>
#include <ctype.h>

int main(void)
{
    int i, j;
    string s = get_string();
    printf("%c", toupper(s[0]));
    
    for (i = 0; j = strlen(s), i < j; i++)
    {
        if (s[i] == ' ')
        {
            printf("%c", toupper(s[i+1]));
        }
    }
    printf("\n");
}
