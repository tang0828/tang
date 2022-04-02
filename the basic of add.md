# tang
test during college

#include <stdio.h>

int sum(int x, int y) {

    int z = x + y;
    
    return z;
    
}
int main() {

    int a;
    
    scanf("%d", &a);
    
    if (a == 3) {
    
        printf("是3\n");
        
    }
    
    else {
    
        printf("不是3\n"); 
        
    }
    int x,y,he;
    
    scanf("%d %d", &x, &y);
    
    he = sum(x, y);
    
    printf("he =%d \n  ", he);
    
    return 0;
    
}
