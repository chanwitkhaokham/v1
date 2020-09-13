#include <stdio.h>
#include <conio.h>
#include <math.h>
#include <stdlib.h>
#include <windows.h>
#define  PI    3.14159265
#define  PCT   100
//system("cls");
//system("COLOR xx");

int loop_choice;            
float a, b, z;

void f_arith(){
       loop_choice = 2;
       int arith_choice;
       while(loop_choice==2){
       a=0, b=0, z=0;       
       system("COLOR 0a");
       printf("\n\t\t\t>>\aArithmetic Operations<<\n");
       printf("\n");
       printf("\t\t\t1.ADD PROGRAM [+]\n");
       printf("\t\t\t2.MINUS PROGRAM [-]\n");
       printf("\t\t\t3.MULTIPLE PROGRAM [*]\n");
       printf("\t\t\t4.DIVIDE PROGRAM [/]\n");
       printf("\n");
       printf("\t\t\tEnter your choice [1-4] : ");
       scanf("%d", &arith_choice);
                   switch(arith_choice){
                   case 1 : { printf("\t\t\t\aEnter A value : ");
                   scanf("%f", &a);
                   printf("\t\t\t\aEnter B value : ");
                   scanf("%f", &b);
                   z = a + b;
                   printf("\n"); 
                   printf("\t\t\t\aValue %.2f + %.2f = %.2f ", a, b, z);
                   } break;
                   case 2 : { printf("\t\t\t\aEnter A value : ");
                   scanf("%f", &a);
                   printf("\t\t\t\aEnter B value : ");
                   scanf("%f", &b);
                   z = a - b;
                   printf("\n"); 
                   printf("\t\t\t\aValue %.2f - %.2f = %.2f ", a, b, z);
                   } break;
                   case 3 : { printf("\t\t\t\aEnter A value : ");
                   scanf("%f", &a);
                   printf("\t\t\t\aEnter B value : ");
                   scanf("%f", &b);
                   z = a * b;
                   printf("\n"); 
                   printf("\t\t\t\aValue %.2f * %.2f = %.2f ", a, b, z);
                   } break;
                   case 4 : { printf("\t\t\t\aEnter A value : ");
                   scanf("%f", &a);
                   printf("\t\t\t\aEnter B value : ");
                   scanf("%f", &b);
                   z = a / b;
                   printf("\n"); 
                   printf("\t\t\t\aValue %.2f / %.2f = %.2f ", a, b, z);
                   } break;
                   default : printf("\n\t\t\t\aError!!! Enter your choice again.");
                   }
       printf("\n\n\t\t\tDo you want to back to main menu ?");
       printf("\n\n\t\t\tPress 1.Yes  Press 2.No  Press 3.Exit : ");
       scanf("%d", &loop_choice);
       system("cls");
       }
       }
       
void f_power(){
       loop_choice = 2;
       int power_choice;
       while(loop_choice==2){
       a=0, b=0, z=0;       
       
       system("COLOR 0b");            
       printf("\n\t\t\t>>\aPower and Root Functions<<\n");
       printf("\n");
       printf("\t\t\t1.POWER PROGRAM \n");
       printf("\t\t\t2.ROOT PROGRAM \n");
       printf("\n");
       printf("\t\t\tEnter your choice [1-2] : ");
       scanf("%d", &power_choice);
                   switch(power_choice){
                   case 1 : { printf("\t\t\t\aEnter A value : ");
                   scanf("%f", &a);
                   printf("\t\t\t\aEnter B value : ");
                   scanf("%f", &b);
                   z = pow(a, b);
                   printf("\n"); 
                   printf("\t\t\t\aValue %.2f ^ %.2f = %.2f ", a, b, z);
                   } break;
                   case 2 : { printf("\t\t\t\aEnter Radical : ");
                   scanf("%f", &a);
                   printf("\t\t\t\aEnter value to find root : ");
                   scanf("%f", &b);
                   z = pow(b, 1.0/a);
                   printf("\n"); 
                   printf("\t\t\t\aRoot %.2f of %.2f = %.2f ", a, b, z);
                   } break;
                   default : printf("\n\t\t\t\aError!!! Enter your choice again.");
                   }
     printf("\n\n\t\t\tDo you want to back to main menu ?");
     printf("\n\n\t\t\tPress 1.Yes  Press 2.No  Press 3.Exit : ");
     scanf("%d", &loop_choice);
     system("cls");
     }
     }
       
void f_tri(){
     loop_choice = 2;
     int tri_choice;
     while(loop_choice==2){
     a=0, b=0, z=0;
     
     system("COLOR 0c");
     printf("\n\t\t\t>>\aTrigonometric Functions<<\n");
     printf("\n");
     printf("\t\t\t1.SIN PROGRAM \n");
     printf("\t\t\t2.COS PROGRAM \n");
     printf("\t\t\t3.TAN PROGRAM \n");
     printf("\n");
     printf("\t\t\tEnter your choice [1-3] : ");
     scanf("%d", &tri_choice);
                switch(tri_choice){
                case 1 : { printf("\t\t\t\aEnter value to SIN : ");
                scanf("%f", &a);
                z = sin(a*PI/180);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f SIN = %.2f ", a, z);
                } break;
                case 2 : { printf("\t\t\t\aEnter value to COS : ");
                scanf("%f", &a);
                z = cos(a*PI/180);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f COS = %.2f ", a, z);
                } break;
                case 3 : { printf("\t\t\t\aEnter value to TAN : ");
                scanf("%f", &a);
                z = tan(a*PI/180);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f TAN = %.2f ", a, z);
                } break;
                default : printf("\n\t\t\t\aError!!! Enter your choice again.");
                }
     printf("\n\n\t\t\tDo you want to back to main menu ?");
     printf("\n\n\t\t\tPress 1.Yes  Press 2.No  Press 3.Exit : ");
     scanf("%d", &loop_choice);
     system("cls");
     }
     }
void f_hyper(){
     loop_choice = 2;
     int hyper_choice;
     while(loop_choice==2){
     a=0, b=0, z=0;
     
     system("COLOR 0d");
     printf("\n\t\t\t>>\aHyperbolic Function<<\n");
     printf("\n");
     printf("\t\t\t1.SINH PROGRAM \n");
     printf("\t\t\t2.COSH PROGRAM \n");
     printf("\t\t\t3.TANH PROGRAM \n");
     printf("\n");
     printf("\t\t\tEnter your choice [1-3] : ");
     scanf("%d", &hyper_choice);
                switch(hyper_choice){
                case 1 : { printf("\t\t\t\aEnter the angle in radians : ");
                scanf("%f", &a);
                z = sinh(a); 
                printf("\n");
                printf("\t\t\t\aHyperbolic Sine of %.2f (in radian) = %.2f ", a, z);
                } break;
                case 2 : { printf("\t\t\t\aEnter the angle in radians : ");
                scanf("%f", &a);
                z = cosh(a);
                printf("\n"); 
                printf("\t\t\t\aHyperbolic Cosine of %.2f (in radian) = %.2f ", a, z);
                } break;
                case 3 : { printf("\t\t\t\aEnter the angle in radians : ");
                scanf("%f", &a);
                z = tanh(a);
                printf("\n"); 
                printf("\t\t\t\aHyperbolic Tangent of %.2f (in radian) = %.2f ", a, z);
                } break;
                default : printf("\n\t\t\t\aError!!! Enter your choice again.");
                }
     printf("\n\n\t\t\tDo you want to back to main menu ?");
     printf("\n\n\t\t\tPress 1.Yes  Press 2.No  Press 3.Exit : ");
     scanf("%d", &loop_choice);
     system("cls");
     }
     }
     
void f_log(){
     loop_choice = 2;
     int log_choice;
     while(loop_choice==2){
     a=0, b=0, z=0;
     
     system("COLOR 0e");
     printf("\n\t\t\t>>\aLogarithmic Functions<<\n");
     printf("\n");
     printf("\t\t\t1.NATURAL LOGARITHM PROGRAM \n");
     printf("\t\t\t2.COMMON (BASE-2)  LOGARITHM PROGRAM \n");
     printf("\t\t\t3.COMMON (BASE-10) LOGARITHM PROGRAM \n");
     printf("\t\t\t4.COMMON (log1p)   LOGARITHM PROGRAM \n");
     printf("\n");
     printf("\t\t\tEnter your choice [1-4] : ");
     scanf("%d", &log_choice);
                switch(log_choice){
                case 1 : { printf("\t\t\t\aEnter value to NATURAL LOGARITHM : ");
                scanf("%f", &a);
                z = log(a);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f convert to NATURAL LOGARITHM = %.2f ", a, z);
                } break;
                case 2 : { printf("\t\t\t\aEnter value to BASE-2 LOGARITHM : ");
                scanf("%f", &a);
                z = log2(a);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f convert to BASE-2 LOGARITHM = %.2f ", a, z);
                } break;
                case 3 : { printf("\t\t\t\aEnter value to BASE-10 LOGARITHM : ");
                scanf("%f", &a);
                z = log10(a);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f convert to BASE-10 LOGARITHM = %.2f ", a, z);
                }break;
                case 4 : { printf("\t\t\t\aCOMMON (log1p) LOGARITHM PROGRAM : ");
                scanf("%f", &a);
                z = log1p(a);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f convert to (log1p) LOGARITHM = %.2f ", a, z);
                } break;
                default : printf("\n\t\t\t\aError!!! Enter your choice again.");
                }
     printf("\n\n\t\t\tDo you want to back to main menu ?");
     printf("\n\n\t\t\tPress 1.Yes  Press 2.No  Press 3.Exit : ");
     scanf("%d", &loop_choice);
     system("cls");
     }
     }
     
void f_oth(){
     loop_choice = 2;
     int oth_choice;
     while(loop_choice==2){
     a=0, b=0, z=0;
     
     system("COLOR 0f");
     printf("\n\t\t\t>>\aOther Functions<<\n");
     printf("\n");
     printf("\t\t\t1.MODULUS FINDER \n");
     printf("\t\t\t2.PERCENTAGE FINDER \n");
     printf("\t\t\t3.CIRCLE AREA FINDER \n");
     printf("\t\t\t4.CIRCLE DIAMETER FINDER \n");
     printf("\t\t\t5.CIRCUMFERENCE FINDER \n");
     printf("\n");
     printf("\t\t\tEnter your choice [1-5] : ");
     scanf("%d", &oth_choice);
                switch(oth_choice){
                case 1 : { printf("\t\t\t\aEnter value to find modulus(x) : ");
                scanf("%f", &a);
                printf("\t\t\t\aEnter value to find modulus(y) : ");
                scanf("%f", &b);
                z = fmod(a, b);
                printf("\n"); 
                printf("\t\t\t\aValue %.2f modulus %.2f = %.2f", a, b, z);
                } break;
                case 2 : { printf("\t\t\t\aEnter number to find percentage : ");
                scanf("%f", &a);
                printf("\t\t\t\aEnter percentage to find value of number : ");
                scanf("%f", &b);
                z = (a*b)/PCT;
                printf("\n"); 
                printf("\t\t\t\a%.2f percentage of %.2f = %.2f", b, a, z);
                } break;
                case 3 : { printf("\t\t\t\aEnter radius to find circle area : ");
                scanf("%f", &a);
                z = PI*(a*a);
                printf("\n"); 
                printf("\t\t\t\aRadius %.2f, Circle area  = %.2f ", a, z);
                } break;
                case 4 : { printf("\t\t\t\aEnter radius to find circle diameter : ");
                scanf("%f", &a);
                z = a*2;
                printf("\n"); 
                printf("\t\t\t\aRadius %.2f, Circle diameter  = %.2f ", a, z);
                } break;
                case 5 : { printf("\t\t\t\aEnter radius to find circumference : ");
                scanf("%f", &a);
                z = 2*(PI*a);
                printf("\n"); 
                printf("\t\t\t\aRadius %.2f, Circumference = %.2f ", a, z);
                } break;
                default : printf("\n\t\t\t\aError!!! Enter your choice again.");
                }
     printf("\n\n\t\t\tDo you want to back to main menu ?");
     printf("\n\n\t\t\tPress 1.Yes  Press 2.No  Press 3.Exit : ");
     scanf("%d", &loop_choice);
     system("cls");
     }
     }















main(){
       int main_choice;
       int colr_loop;
       loop_choice = 1;
       
       for(colr_loop=0;colr_loop<=5;colr_loop++){
       printf("\n\n\n\n\n\n\n\n\n\n\t\t\t\t ...Loading...\n");
       system ( "color 01" );
       Sleep ( 100 );
       system ( "color 02" );
       Sleep ( 100 );
       system ( "color 03" );
       Sleep ( 100 );
       system ( "color 04" );
       Sleep ( 100 );
       system ( "color 05" );
       Sleep ( 100 );
       system ( "color 06" );
       Sleep ( 100 );
       system ( "color 07" );
       Sleep ( 100 );
       system ( "color 08" );
       Sleep ( 100 );
       system ( "color 09" );
       Sleep ( 100 );
       system( "color 0A" );
       Sleep( 100 );
       system( "color 0B" );
       Sleep( 100 );
       system( "color 0C" );
       Sleep( 100 );
       system( "color 0D" );
       Sleep( 100 );
       system( "color 0E" );
       Sleep( 100 );
       system( "color 0F" );
       Sleep( 100 );
       system("cls");
       }
while(loop_choice==1){
       printf("\a\a\a\n\t\t\t<3================================<3\n");
       printf("\n\t\t\t SIMPLE MATHERMATICS CALCULATOR\n");
       printf("\n\t\t\t<3================================<3\n");
       printf("\n\t\t\t1.Arithmetic Operations\n");
       printf("\n\t\t\t2.Power and Root Functions\n");
       printf("\n\t\t\t3.Trigonometric Functions\n");
       printf("\n\t\t\t4.Hyperbolic Function\n");
       printf("\n\t\t\t5.Logarithmic Functions\n");
       printf("\n\t\t\t6.Other Functions\n");
       printf("\n\t\t\t0.Exit Program\n\n");
       printf("\n\t\t\tEnter your choice [1-6 or 0] : ");
       scanf("%d", &main_choice);
       system("cls");
       
       
       switch(main_choice){
       case 0 : exit(0);
                break;         
       case 1 : f_arith();
                break;
       case 2 : f_power();
                break;
       case 3 : f_tri();
                break;
       case 4 : f_hyper();
                break;
       case 5 : f_log();
                break;
       case 6 : f_oth();
                break;
       default :{ system("cls");
                  printf("\a\n\t\t\tError!!! Enter your choice again.");
                  printf("\a\n\t\t\tPress any keys to continue...");
                  getch();
                  system("cls");
                  }
       
       }         

                
                
       }
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       
       //getch();
       // <3 For My Parents and Friends.
       //Code by Anuwat Khongchuai AKA. NetMonsterz
       }
