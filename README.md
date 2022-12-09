# RC-seach-engine-backend-code
Skip to content
Search or jump to…
Pull requests
Issues
Codespaces
Marketplace
Explore
 
@Javedzuck12 
Javedzuck12
/
RC-seach-engine-backend-code
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
RC-seach-engine-backend-code/vechice appinfo.c
@Javedzuck12
Javedzuck12 Add files via upload
Latest commit 593853c 2 minutes ago
 History
 1 contributor
45 lines (44 sloc)  1.31 KB

#include <stdio.h>
#include<string.h>
struct fw{
    char  car_name[20];
    char saftey[5];
    int fuel,serial;
    float price;

};
int main()
{
    struct fw car[3];
    for(int i=0;i<=3;i++){
        printf("Enter the details of the car %d:\n",i+1);
        printf("Enter the details of the car:");
        scanf("%s",&car[i].car_name);
        printf("Does your have airbag ?\n Type yes if avaiable else NO:");
        scanf("%s",&car[i].saftey);
        printf("Enter the seraial number of the car:");
        scanf("%d",&car[i].serial);
        printf("enter the price of the car:");
        scanf("%d",&car[i].price);
    }
    printf("The details of each car:\n");
    for(int i=0;i<=3;i++){
        printf("Details of the car %d \n",i+1);
        printf("car name \t %s\n",car[i].car_name);
        printf("airbag \t %s\n",car[i].saftey);
        if (car[i].fuel==1){
            printf("Fuel\t CNG\n");
        }
        else if (car[i].fuel==2){
            printf("Fuel\t petrol\n");
        }
         else if (car[i].fuel==3){
            printf("Fuel\t Diesel\n");
        }
         else if (car[i].fuel==2){
            printf("Fuel\t Electricity\n");
        }
        printf("serial\t %d\n",car[i].serial);
        printf("price\t %d\n",car[i].price);
    }
    return 0;
}
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
RC-seach-engine-backend-code/vechice appinfo.c at main · Javedzuck12/RC-seach-engine-backend-codeSkip to content
Search or jump to…
Pull requests
Issues
Codespaces
Marketplace
Explore
 
@Javedzuck12 
Javedzuck12
/
RC-seach-engine-backend-code
Public
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
RC-seach-engine-backend-code/vechice appinfo.c
@Javedzuck12
Javedzuck12 Add files via upload
Latest commit 593853c 2 minutes ago
 History
 1 contributor
45 lines (44 sloc)  1.31 KB

#include <stdio.h>
#include<string.h>
struct fw{
    char  car_name[20];
    char saftey[5];
    int fuel,serial;
    float price;

};
int main()
{
    struct fw car[3];
    for(int i=0;i<=3;i++){
        printf("Enter the details of the car %d:\n",i+1);
        printf("Enter the details of the car:");
        scanf("%s",&car[i].car_name);
        printf("Does your have airbag ?\n Type yes if avaiable else NO:");
        scanf("%s",&car[i].saftey);
        printf("Enter the seraial number of the car:");
        scanf("%d",&car[i].serial);
        printf("enter the price of the car:");
        scanf("%d",&car[i].price);
    }
    printf("The details of each car:\n");
    for(int i=0;i<=3;i++){
        printf("Details of the car %d \n",i+1);
        printf("car name \t %s\n",car[i].car_name);
        printf("airbag \t %s\n",car[i].saftey);
        if (car[i].fuel==1){
            printf("Fuel\t CNG\n");
        }
        else if (car[i].fuel==2){
            printf("Fuel\t petrol\n");
        }
         else if (car[i].fuel==3){
            printf("Fuel\t Diesel\n");
        }
         else if (car[i].fuel==2){
            printf("Fuel\t Electricity\n");
        }
        printf("serial\t %d\n",car[i].serial);
        printf("price\t %d\n",car[i].price);
    }
    return 0;
}
Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
RC-seach-engine-backend-code/vechice appinfo.c at main · Javedzuck12/RC-seach-engine-backend-code
