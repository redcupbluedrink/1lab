#include <stdio.h>
#include <math.h>
/* 1 
int main() {

    int y = 2;
    int z = 4;
    float t = 5 / (1 + powf(y,2));
    float x = 2 * y + 3 * sinh(t) - z;
    printf("%.2f", x); 
}
*/

/* 2
int main() {
    
    float t = 0.5;
    int z = 6;
    float y = t + (2 * (cos(z) / sin(z)));
    float x = (3 * (y * y)) / ((4 * (sin(z) / cos(z))) - (2 * (t * t)));
    printf("%.2f", x);
}
*/

/* 3
int main() {
	
    int t = 1;
    int z = 3;
    float y = sin(t);
    float x = ((4 * (y*y)) / (4 * y * exp(z) - 2 * powf(t,3)));
    
    printf("%.2f", x);
    
}
*/

/* 4 
int main() {
	
	int t = 2;
	int z = 3;
	float y = cos(t + z);
	float x = (4 * (log(powf(y,3)))) - (z / t);
	
	printf("%.2f", x);
		
}
*/

/* 5 
int main() {
	
	int y = 2;
	int z = 4;
	float t = sin(2+z);
	float x = (6 * powf(t,2)) - (((1/tan(z)) + 1) / powf(y,2));
	
	printf("%.4f", x);
}
*/

/* 6
int main() {
	int z = 1;
	int t = 2;
	float y = tan(t) + z;
	float x = ((8 * powf(z,2)) + 1) / ((y * exp(t)) + powf(t,2));
	
	printf("%.2f", x);
}
*/
