#include <stdio.h>
int max(int *cisla, int n){
    int max = *cisla;
    for(int i = 0; i<n; i++){
        if(max<*(cisla + i)){
            max = *(cisla + i);
        }
    }
    return max;
}
int main() {
    int numbers[] = {8, 16, 78, 3, 5, 9, 41, 69};
    printf("%d", max(numbers, sizeof(numbers) / 4));
    return 0;
}
