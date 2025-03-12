//# c-18
//hollow square
#include<stdio.h>
int main(){
    int n=4,m=4;
    for(int i=1;i<=n;i++){
        for(int j=1;j<=m;j++){
            if(i==1||i==n||j==1||j==m){
            printf("* ");
        }
        else{
            printf("  ");
        }
        }
        printf("\n");
        }
        
    return 0;
}
