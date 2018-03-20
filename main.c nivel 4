#include <stdio.h>
#include <stdlib.h>
//casteo
int main()
{
    int numero;
    char seguir = 's';
    int contpares=0;
    int contnumeros=0;
    int acum=0;
    float promedio;
    int min;
    int max;
    int flag =0;

    while(seguir== 's')
    {
        printf("\n ingrese un numero: ");
        scanf("%d", &numero);

    while(numero<=0)
        {
            printf("\nReingrese un numero: ");
            scanf("%d", &numero);
        }

        if(numero%2==0)
        {
            contpares++;
        }
        contnumeros++;
        acum+=numero;// acumulador= acumulador + numero

       /* if(flag==0)
        {
            max = numero;
            min = numero;
            flag = 1;
        }
        if(numero>max)
        {
            max= numero;
        }
        If(numero<min)
        {
            min= numero;
        }*/ //forma larga//

        if(flag == 0 || numero > max)
        {
            max=numero;

        }
        if(flag == 0 || numero < min)
        {
            min =numero;
            flag=1;
        }


        printf("\nDesea continuar?: ");
        seguir = getche();

     }

     promedio = (float)acum/contnumeros;





    printf("\nCantidad de numeros pares: %d", contpares );
    printf("\nEl promedio es: %f", promedio);
    printf("\nLa suma de todos los numeros es: %d", acum);
    printf("\nEl numero maximo es: %d", max);
    printf("\nEl numero minimo es: %d", min);








    return 0;
}
