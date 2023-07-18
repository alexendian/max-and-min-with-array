# max-and-min-with-array
#include<stdio.h>
int main(){

    int num[1000],n,i;
    printf("how many number?: ");
    scanf("%d",&n);


    for(i=0;i<n;i++){
        printf("num[%d]",i);
        scanf("%d",&num[i]);
    }
    int max = num[0];
    for(i=0;i<n;i++){
        if(max<num[i]){
            max=num[i];
        }
    }
    printf("max=%d\n",max);
    return 0;
}
