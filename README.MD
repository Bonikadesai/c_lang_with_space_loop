><u>**Aim**</u> : <b>Q.1 Write a Program to print the below pattern using nested for loop.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3 2 1<br>
&nbsp;&nbsp;&nbsp;4 3 2 1<br>
5 4 3 2 1 <br></b>

><u>**Program**</u> : 

       #include<stdio.h>

        void main(){
            int i,j,k;
            for(i=1;i<=5;i++){
                for(k=5;k>i;k--){
                    printf(" ");
                }
                for(j=i;j>=1;j--){
                    printf("%d",j);
                }
                printf("\n");
            }
        }

<br>

><u>**Aim**</u> : <b>Q.2 Write a Program to print the below pattern using nested for loop.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4 5<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3 4 5<br>
&nbsp;&nbsp;&nbsp;2 3 4 5<br>
1 2 3 4 5 <br></b>

><u>**Program**</u> : 

       #include<stdio.h>

        void main(){
            int i,j,k;
            for(i=5;i>=1;i--){
                for(k=1;k<i;k++){
                    printf(" ");
                }
                for(j=i;j<=5;j++){
                    printf("%d",j);
                }
                printf("\n");
            }
        }

<br>

><u>**Aim**</u> : <b>Q.3 Write a Program to print the below pattern using nested for loop.<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4 4<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3 3 3<br>
&nbsp;&nbsp;&nbsp;2 2 2 2<br>
1 1 1 1 1 <br></b>

><u>**Program**</u> : 

       #include<stdio.h>

        void main(){
            int i,j,k;
            for(i=1;i<=5;i++){
                for(k=5;k>i;k--){
                    printf(" ");
                }
                for(j=i;j>=1;j--){
                    printf("%d",i);
                }
                printf("\n");
            }
        }

<br>

><u>**Aim**</u> : <b>Q.4 Write a Program to print the below pattern using nested for loop.<br>
1 0 1 0 1<br>
&nbsp;&nbsp;&nbsp;0 1 0 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1 0 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;0 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1<br></b>

><u>**Program**</u> : 

       #include<stdio.h>

            void main(){
                int i,j,k;
                for(i=5;i>=1;i--){
                    for(k=5;k>i;k--){
                        printf(" ");
                    }
                    for(j=i;j>=1;j--){
                        if(j%2==0){
                            printf("0",j);
                        }
                        else{
                            printf("1",j);
                        }
                    }
                    printf("\n");
                }
            }

<br>

><u>**Aim**</u> : <b>Q.5 Write a Program to print the below pattern using nested for loop.<br>
5 4 3 2 1<br>
&nbsp;&nbsp;&nbsp;4 3 2 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;3 2 1 <br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2 1<br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;1<br></b>

><u>**Program**</u> : 

       #include<stdio.h>

            void main(){
                int i,j,k;
                for(i=5;i>=1;i--){
                    for(k=5;k>i;k--){
                        printf(" ");
                    }
                    for(j=i;j>=1;j--){
                        
                        printf("%d",j);
                    }
                    printf("\n");
                }
            }

<br>

><u>**Aim**</u> : <b>Q.7 Write a Program to print the below pattern using nested for loop.<br>
41<br>
41 42<br>
41 42 43<br>
41 42 43 44<br>
41 42 43 44 45<br></b>

><u>**Program**</u> : 

       #include<stdio.h>

            void main(){
                int i,j;
                for(i=41;i<=45;i++){
                    for(j=41;j<=i;j++){
                        printf("%d ",j);
                    }
                    
                    printf("\n");
                }
                
            }

<br>
