### Hi there 👋
I'm Ibrahim from morocco, and I do content on Desing and Development. I really enjoy learning languages and frameworks like react Native, as well as work in WordPress I also enjoy wireframing, and desing in general. 
#include <stdio.h>
/*print fahrenheit-celsuis tabel */ 
#define LOWER 0       // lower limit of table 
#define UPPER 300      // upper limit 
#define STEP 20         // step size 
int main()
{
    int fahr;
    
    for (fahr = LOWER; fahr <= UPPER; fahr = fahr + STEP)
        printf("%3d %6.1f\n", fahr, (5.0/9.0)*(fahr-32));
}
