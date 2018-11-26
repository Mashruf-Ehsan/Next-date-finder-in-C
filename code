#include <stdio.h>

int main(void)
{
    int d,m,y;
    printf("Enter Day: ");
    scanf("%d",&d);
    printf("Enter Month: ");
    scanf("%d",&m);
    printf("Enter Year: ");
    scanf("%d",&y);

    //IF 31 Days Month
    if(m==1||m==3||m==5||m==7||m==8||m==10||m==12){
        //If Not December
        if(m<12){
            if(d>=1 && d<=30){
                d++;
                printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
            }
        else if(d==31){
            d=1;
            m++;
            printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
        }
        else
        printf("\nInvalid Date !\n");
        }
        //If December
        else{
            if(d>=1 && d<=30){
                d++;
                printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
            }
        else if(d==31){
            d=1;
            m=1;
            y++;
            printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
        }
        else
        printf("\nInvalid Date !\n");
        }
    }
    //31 Days Complete

    //If 30 Days Month
    else if(m==4||m==6||m==9||m==11){
        if(d>=1 && d<=29){
            d++;
            printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
        }
        else if(d==30){
            d=1;
            m++;
            printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
        }
        else
        printf("\nInvalid Date !\n");
    }
    //30 Days Month Complete

    //February
    else if(m==2){
            //Leap year
            if(y%400==0 || y%4==0 && y%100!=0){
                if(d>=1 && d<=28){
                        d++;
                    printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
                }
                else if(d==29){
                    d=1;
                    m=3;
                    printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
                }
                else
                    printf("\nInvalid Date !\n");
            }
            //Leap year done

            //If Not Leap year
            else{
                if(d>=1 && d<=27){
                        d++;
                    printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
                }
                else if(d==28){
                    d=1;
                    m=3;
                    printf("\nNext Day: %d\nNext Month: %d\nNext Year: %d\n",d,m,y);
                }
                else
                    printf("\nInvalid Date !\n");
            }
            //Not Leap year done
    }

    else
        printf("\nInvalid Date !\n");

    return 0;
}
