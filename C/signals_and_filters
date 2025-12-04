/*************************
Includes
**************************/
#include <stdio.h>
#include <math.h>

/*************************
Macros
**************************/
#define M_PI 3.14159265358979323846
#define NUM_OF_SAMPLES 62

/*************************
Function Prototypes
**************************/
void fillArray(double*);
void printArray(double*);
void applySin(double*);

/*************************
main
**************************/
int main()
{
	double* xs;
	fillArray(xs);
	applySin(xs);
	printArray(xs);
}

/*************************
Functions
**************************/
// Applies sin function to array or rads
void applySin(double* s) {
	for(int i = 0; i <= NUM_OF_SAMPLES; i++) {
		s[i] = sin(s[i]);
	}
}

// Fills array with iterative doubles -> radians
void fillArray(double* s) {
	double n = 0.0;
	for(int i = 0; i <= NUM_OF_SAMPLES; i++) {
		s[i] = n;
		n = n + 0.1;
	}

}

// Print Function
void printArray(double* s) {
	for(int i = 0; i <= NUM_OF_SAMPLES; i++) {
		printf("%f\n", s[i]);
	}
}
