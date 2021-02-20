# Excercise-5
Set of excercises
# 5-1
```c
#include <conio.h>
#include <stdio.h>

//program to convert from centigrades to farenheit

float t,f;

int main(){
	printf ("Insert the centigrades that you want to turn into farenheit\n");
	scanf("%f", &t);
	f = (1.8 * t) + 32;  //conversion
	printf("The temperature is equal to %f farenheit",f);
	getch();
	return 0;
}
```

# 5-2
```c
#include <stdio.h>
#include <conio.h>

//5-2, Program to calculate volume of a sphere
float v, r, pi = 3.14159;
int main(){
	printf("Introduce the radio of the sphere in cm\n");
	scanf("%f", &r);
	v = 1.33333 * pi * (r * r * r);
	printf("\nThe volume of the sphere is %f cm^3",v);
	getch();
	return 0;
	
}
```

# 5-3
```c
#include <conio.h>
#include <stdio.h>
//Program to calculate the perimeter of a rectangle 5-3
 float h, p, w;
int main(){
	printf("Enter the height of the rectangle followed by the width\n");
	scanf("%f %f", &h, &w);
	p = w + h;
	p = 2 * p;
	printf("The perimeter of your rectangle is %f", p);
	getch();
	return 0;
	
	
}
```

# 5-4
```c
#include <stdio.h>
#include <conio.h>
//program to convert from km/h to mph
float k1, k;
int main(){
	printf("Introduce the km/h\n");
	scanf("%f", &k);
	k1 = k;
	k = k * 0.6213712;
	printf("The %f km/h are equal to %f mph", k1, k);
	getch();
	return 0;
}
```
# 5-5
```c
#include <stdio.h>
#include <conio.h>
//program to convert from hours to minutes
int h, m;
int main(){
	printf("Introduce the hours followed by the minutes\n");
	scanf("%d %d", &h, &m);
	h = h * 60;
	m = m + h;
	printf("It is equal to %d minutes", m);
	getch();
	return 0;
```

# 5-6
```c
#include <stdio.h>
#include <conio.h>
//program to convert from minutes to hours
int mt, h, m;
int main(){

printf("Insert the total minutes\n");
scanf("%d", &mt);
h = mt/60;
printf("It is equal to %d hours and ", h);
m = -h * 60 + mt;
printf("%d minutes", m);
getch();
return 0;
}
```
