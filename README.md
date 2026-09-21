#include <stdio.h>

int main() {

    int grades;

    printf("ENTER THE SCORE: ");
    scanf("%d", &grades);

    if (grades < 0 || grades > 100) {
        printf("Invalid score\n");
    }
    else if (grades >= 90) {
        printf("Grade A\n");
    }
    else if (grades >= 80) {
        printf("Grade B\n");
    }
    else if (grades >= 70) {
        printf("Grade C\n");
    }
    else if (grades >= 60) {
        printf("Grade D\n");
    }
    else {
        printf("Grade F\n");
    }

    return 0;
}
