# C-Program-to-Calculate-Area-Of-a-Circle

Area of Circle in C
Here, in this page we will discuss the program to find area of circle in C programming language.

The area of a circle can be found by using the formula:
Area of circle= 𝝅*R* R , or
Area of circle = (𝝅*D* D)/4

Area of circle in C
While loop in C
Working:-
User gives an input
The input is stored in a float type variable say radius.
Another float type variable is taken say area and variable pi initialized with 3.14.
Now using the formula we find the area of the circle of radius radius and store it in area.
                          area= pi* radius* radius;

Print the value of area.
Code in C
Run
#include <stdio.h>

int main(){
    float r =3, pi=3.14, area;
    
    area=pi*r*r;
    printf("Area of circle is %.2f", area);
}
Output
Area of circle is 28.26
Algorithm using diameter:-
User gives an input
The input is stored in a float type variable say d.
Another float type variable is taken say area and variable pi initialized with 3.14.
Now using the formula we find the area of the circle of diameter d and store it in area.
                          area= (pi* d* d)/4;

Print the value of area.
Code in C
Run
#include <stdio.h>
int main(){
    float d = 6, pi=3.14, area;
    
    area=(pi*d*d)/4;
    printf("Area of circle is %.2f", area);
}
Output
Area of circle is 28.26
