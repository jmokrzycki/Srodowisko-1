
Zad 1

```c
/*Napisac program, ktory wczyta liczbe calkowita i wypisze czy jest wieksza od 5*/

#include <stdio.h>
main (){

  int liczba;
  printf("Podaj liczbe \n");
  scanf("%d", &liczba);
  printf ("%d\n",liczba);
  if(liczba>5)
    printf("Liczba %d jest większa od 5 \n",liczba);
  else 
    printf("Liczba %d jest mniejsza lub rowna 5 \n",liczba);
  return 0;
  }
  
  ```
