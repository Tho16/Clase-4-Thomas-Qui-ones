# Guias-

Thomas Quiñones

Clase 4-Primeros Codigos
1) #include<stdio.h >
#include <stdlib.h>

int main()
{
int num1=0, num2=0;
printf("Ingrese un numero");
scanf("%d",&num1);
printf("Ingrese otro numero");
scanf("%d",&num2);
printf("los numeros ingresados son %d\n",num1);
printf("los numeros ingresados son  %d\n",num2);
return 0;
}

2) #include<stdio.h >
#include <stdlib.h>

int main()
{
int a=0, b=0, Area=0, Perimetro=0;
printf("Ingrese la altura del rectangulo");
scanf("%d",&a);
printf("Ingrese la base del rectangulo");
scanf("%d",&b);
Area=a*b;
Perimetro=2*a+2*b;
printf("el area del rectangulo es %d\n",Area);
printf("el perimetro del rectangulo es  %d\n",Perimetro);
return 0;
}

3) #include<stdio.h >
#include <stdlib.h>

int main()
{
int H=0, M=0, PorcH=0, PorcM=0, Total=0;
printf("Ingrese la cantidad de hombres");
scanf("%d",&H);
printf("Ingrese la cantidad de mujeres");
scanf("%d",&M);
Total=H+M;
PorcH=H*100/Total;
PorcM=M*100/Total;
printf("el porcentaje de hombres postulados es %d\n",PorcH);
printf("el porcentaje de mujeres postuladas es %d\n",PorcM);
return 0;
}

4) #include<stdio.h >
#include <stdlib.h>

int main()
{
int Fuerza=0, Presion=0, Area=0;
printf("Ingrese la fuerza");
scanf("%d",&Fuerza);
printf("Ingrese el area");
scanf("%d",&Area);
Presion=Fuerza/Area;
printf("la presion aplicada sobre la superficie es %d\n",Presion);
return 0;
}

5) #include<stdio.h >
#include <stdlib.h>

int main()
{
int R1=0, R2=0, R3=0, R4=0, R5=0, Rt=0;
printf("Ingrese las resistencias");
scanf("%d",&R1);
scanf("%d",&R2);
scanf("%d",&R3);
scanf("%d",&R4);
scanf("%d",&R5);
Rt=R1+R2+R3+R4+R5;
printf("r1=%d\n",R1);
printf("r2=%d\n",R2);
printf("r3=%d\n",R3);
printf("r4=%d\n",R4);
printf("r5=%d\n",R5);
printf("rt=%d\n",Rt);
return 0;
}

6) #include<stdio.h >
#include <stdlib.h>

int main()
{
int Num=0, Total=0;
printf("Ingrese un numero");
scanf("%d",&Num);
Total=Num/8;
printf("la octava parte es %d\n",Total);
return 0;
}

7) #include<stdio.h >
#include <stdlib.h>

int main()
{
int Num=0, Num2=0;
printf("Ingrese un numero");
scanf("%d",&Num);
printf("Ingrese otro numero");
scanf("%d",&Num2);
if(Num<Num2)
{
printf("El numero mayor es %d", Num2);
}
else
{
if (Num2<Num)
{
printf("El numero mayor es %d", Num);
}
else
{
printf("son iguales");	
}
}
return 0;
}

8) #include<stdio.h >
#include <stdlib.h>

int main()
{
int hora=0, edad=0, Promo=0, TotalCimp=0, TotalSimp=0;
printf("Ingrese edad");
scanf("%d",&edad);
printf("Ingrese las horas");
scanf("%d",&hora);
Promo=hora*50;
if(edad>=50)
{
TotalSimp=Promo-(Promo*20/100);
}
else
{
if (edad>=60)
{
TotalSimp=Promo-(Promo*30/100);
}
else
{
if (edad>=70)
{
TotalSimp=Promo-(Promo*50/100);	
}
else
{
TotalSimp=Promo;
}	
}
}
TotalCimp=TotalSimp+(Promo*33/100);
printf("el importe total con impuestos es %d", TotalCimp);
printf("y el importe total sin impuestos es %d", TotalSimp);
return 0;
}

9) #include<stdio.h >
#include <stdlib.h>

int main()
{
float Horas=0, Sueldo=0;
char Categoria;
printf("Ingrese su categoria");
scanf("%c",&Categoria);
printf("Ingrese la cantidad de horas trabajadas");
scanf("%f",&Horas);
if(Categoria=='A')
{
Sueldo=Horas*200;}
else
{if (Categoria=='B')
{
Sueldo=Horas*180;
}
else
{
if (Categoria=='C')
{
Sueldo=Horas*150;	
}
else
{
Sueldo=Horas*0;
}	
}
}
printf("Su sueldo es %f", Sueldo);
return 0;
}

10) #include<stdio.h >
#include <stdlib.h>

int main()
{
int Total=0, Sueldo=0, Cat=0, Hijos=0;
printf("Ingrese su sueldo");
scanf("%d",&Sueldo);
printf("Ingrese la categoria");
scanf("%d",&Cat);
if(Cat==1)
{
Total=Sueldo+(Sueldo*10/100);
}
else
{
if (Cat==2)
{
Total=Sueldo+(Sueldo*20/100);
}
}
printf("ingrese su cantidad de hijos");
scanf("%d",&Hijos);
if(Hijos<4)
{
Total=Total+(Hijos*500);
}
else
{
Total=Total+(Hijos*300);
}
printf("su sueldo es %d",Total);
return 0;
}

11) #include<stdio.h >
#include <stdlib.h>

int main()
{
int peso=0, Alt=0, Masa=0;
printf("Ingrese su peso");
scanf("%d",&peso);
printf("Ingrese la altura");
scanf("%d",&Alt);
Masa=peso/(Alt*Alt);
if(Masa<20)
{
printf("su estado es de bajo peso");
}
else
{
if (Masa<=25)
{
printf("su estado es de un peso ideal");
}
else
{
printf("su estado es el excedido");
}
}
return 0;
}

12) #include<stdio.h >
#include <stdlib.h>

int main()
{
float Sup1,Pob1,Sup2,Pob2,Sup3,Pob3,Dpob1,Dpob2,Dpob3;
printf("Ingrese la superficie y poblacion del primer pais");
scanf("%f%f",&Sup1,&Pob1);
Dpob1=Pob1/Sup1;
printf("Ingrese la superficie y poblacion del segundo pais");
scanf("%f%f",&Sup2,&Pob2);
Dpob2=Pob2/Sup2;
printf("Ingrese la superficie y poblacion del tercer pais");
scanf("%f%f",&Sup3,&Pob3);
Dpob3=Pob3/Sup3;
if(Dpob1>Dpob2)
{
printf("el pais mas poblado es el primero");
}
else
{
if (Dpob2>Dpob3)
{
printf("el pais mas poblado es el segundo");
}
else
{
printf("el pais mas poblado es el tercero");
}
}
return 0;
}

13) #include<stdio.h >
#include <stdlib.h>

int main()
{
float Num1,Num2,Num3;
printf("Ingrese tres valores");
scanf("%f%f%f",&Num1,&Num2,&Num3);
if(Num1==Num2&&Num2==Num3)
{
printf("todos los valores son iguales");
}
else
{
if (Num1==Num2|| Num2==Num3|| Num1==Num3)
{
printf("dos valores iguales y uno distinto");
}
else
{
printf("Son todos distintos");
}
}
return 0;
}

14) #include<stdio.h >
#include <stdlib.h>

 main()
{
float Hora,Segs,Mins,UniF,Total;
printf("Ingrese horas,minutos y segundos");
scanf("%f%f%f",&Hora,&Mins,&Segs);
printf("Ingrese unidad final");
scanf("%f",&UniF);
if(UniF==1)
{
Total=Segs+(Hora*3600)+(Mins*60);	
printf("Segundos=%f",Total);
}
else
{
if (UniF==2)
{
Total=Mins+(Hora*60)+(Segs/60);
printf("Mins=%f", Total);
}
else
{if (UniF==3)
{
Total=Hora+(Mins/60)+(Segs*3600);
printf("Horas=%f", Total);
}
}
}
return 0;
}

15) #include<stdio.h >
#include <stdlib.h>

 main()
{
int Num1,Num2,Num3;
printf("Ingrese tres numeros");
scanf("%d%d%d",&Num1,&Num2,&Num3);
if(Num1<Num2&&Num2<Num3)
{
printf("Fueron Ingresados en forma ascendente");
}
else
{
printf("No es ascendente");
}
return 0;
}
