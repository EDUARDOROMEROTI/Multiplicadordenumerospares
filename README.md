# Multiplicadordenumerospares
Multiplicador de números pares até dez


#include <stdio.h>

int main ()

{
	
	for (int number = 1; number <= 20; number++) {
		if (number %2 ==0) {
			printf ("%d\n", number);
			
		}
	}
}
