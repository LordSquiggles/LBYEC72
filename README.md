# LBYEC72

```
#include <stdio.h>
#include <stdlib.h>

#define PI 3.14159

void printNameCourse();
float computeCircleArea(float functionRadius);

int main()
{
	printNameCourse();
	
	float area;
	float radius;
	
	radius=10;
	
	area = computeCircleArea(radius);
	printf("The area is in %f\n", area);
	return EXIT_SUCCESS;
}

void printNameCourse(){


puts("Choco Jose Antonio G.");
puts("Hello LBYEC 72!");


}

float computeCircleArea(float functionRadius){
	return PI * functionRadius * functionRadius;
}
```

![screenshot](https://github.com/LordSquiggles/LBYEC72/blob/master/Screenshot.PNG)
