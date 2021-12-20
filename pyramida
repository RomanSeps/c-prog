#include <stdio.h>

int main() {
 int x, space, levels, y = 0;
   scanf("%d", &levels);
   for (x = 1; x <= levels; ++x, y = 0) {
      for (space = 1; space <= levels - x; ++space) {
         printf("  ");
      }
      while (y != 2 * x - 1) {
         printf("* ");
         ++y;
      }
      printf("\n");
   }
    return 0;
}
