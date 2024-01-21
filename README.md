<!-- Markdown Tutorial-->

_p_ __y__ ~~r~~ `amid`
---

### right half pyramid cross multiplication

//write a programme that multiply row and column and print as pyramid pattern

[x] pattern
[x] pyramid
[x] multiply row and column
[] divide

```c
#include<stdio.h>
int main()
{
    while(1)
    {
        int num,row,column;
        printf("Enter the number : ");
        scanf("%d",&num);

        for(row=1; row<=num; row++)
        {
            for(column=1; column<=row; column++)
            {
                printf("%d ",row*column);
            }
            printf("\n");
        }
    }
}
```  
<!--![Demo](./images/multiplicationpyramid.png)-->

<img src="./images/multiplicationpyramid.png" width="250" title="demo"/>

//write a programme that print pyramid row number only

```c
#include<stdio.h>
int main()
{
    while(1)
    {
        int num,row,column;
        printf("Enter the number : ");
        scanf("%d",&num);

        for(row=1; row<=num; row++)
        {
            for(column=1; column<=row; column++)
            {
                printf("%d ",row);
            }
            printf("\n");
        }
    }
}
```  
<img src="./images/row.png" widh="300" title="demo"/>

</br>

//write a programme that print half pyramid with remainder

```c
#include<stdio.h>
int main()
{
    int num,row,column;
    printf("Enter the number : ");
    scanf("%d",&num);

    for(row=1; row<=num; row++)
    {
        for(column=1; column<=row; column++)
        {
            printf("%d",row%2);
        }
        printf("\n");
    }
    getchar();
}
```

![remainder](./images/remainder.png)

conti~~nue~~

//write a programme that print pyramid pattern with column remainder

```c
#include<stdio.h>
int main()
{
    int num,row,column;
    printf("Enter the number : ");
    scanf("%d",&num);

    for(row=1; row<=num; row++)
    {
        for(column=1; column<=row; column++)
        {
            printf("%d",col%2);
        }
        printf("\n");
    }
    getchar();
}
```  

<img src="./images/remaindercolumn.png" width="500" title="remaindercolumn" />  

//write a programme that pring right half pyramid with star...

```c
#include<stdio.h>
int main()
{
    int num,row,column;
    printf("Enter the number : ");
    scanf("%d",&num);

    for(row=1; row<=num; row++)
    {
        for(column=1; column<=row; column++)
        {
            printf("*");
        }
        printf("\n");
    }
    getchar();
}
```

<img src="./images/star.png" width="500" title="Star"/>  

// write a programme that print pyramid with alphabet  

```c
#include<stdio.h>
int main()
{
    int num,row,column;
    printf("Enter the number : ");
    scanf("%d",&num);

    for(row=1; row<=num; row++)
    {
        for(column=1; column<=row; column++)
        {
            printf("%c",column+64);
        }
        printf("\n");
    }
    getchar();
}
```  

<img src="./images/alphabet.png" width="300" title="demo"/>  

con_t_i~~nue~~