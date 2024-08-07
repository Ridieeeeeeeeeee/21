21
<br>#include <stdio.h>

int main()
{  int  val,i=0,sum=0,avg,n;
    printf("How many numbers you want to enter:");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
    printf("Enter the [%d] number:",i);
    scanf("%d",&val);
    sum=sum+val;
    }
    printf("sum=%d",sum);
    avg=sum/n;
    printf("average=%d",avg);
    printf("Hello World");

    return 0;
}

