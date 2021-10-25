#include <stdio.h>

int main() {
    // Write C code here
    int n;
    scanf("%d",&n);
    int i,a[n];
    for(i=0;i<n;i++)
    {
        scanf("%d",&a[i]);
    }
    for(i=0;i<n;i++)
    {
        if(a[i]%2==0&&i%2==0)
        {
            printf("%d ",a[i]);
        }
    }
    return 0;
}