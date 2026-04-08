#include <stdio.h>
#include <stdlib.h>

void main(int argc, char *argv[])
{
if (argc == 1)
{
    printf("voce nao digitou nada");
    exit(0);
}
else
{
    printf("voce digitou %s", argv[1]);
}
printf("\ncriado por Benjamim Messias\n");
}
