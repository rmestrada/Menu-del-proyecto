# Menu-del-proyecto

#include <stdio.h>

int main()
{
    char t,d,h,eleccion;

    printf("Bienvenido al encuentratodo, ¿que desea utilizar?\n");
    printf("Si desea entrar en los datos pulse d\n");
    printf("Si desea entrar en las tablas estadisticas pulse t\n");
    printf("Si desea ayuda sobre como funciona el programa pulse h\n");
    scanf("%c", &eleccion);

    switch (eleccion)
    {
 case'd':
     printf("A seleccionado la seccion datos");
    break;

case't':
    printf("A selecionado la seccion tablas estadisticas");
    break;
case'h':
    printf("El encuentratodo es un programa con una base de datos de archivos csv el cual permite al usuario encontrar datos estadisticos acerca de (tema indicado)");
    break;
    default:
    printf("Por favor, seleccione una de las letras indicadas");
    }

    return 0;
}
