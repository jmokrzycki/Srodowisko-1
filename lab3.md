Zad 1

```c
/*Napisac program, ktory wczyta liczbe calkowita i wypisze czy jest wieksza od 5*/


  int liczba;
  printf("Podaj liczbe \n");
  scanf("%d", &liczba);
  printf ("%d\n",liczba);
  if(liczba>5)
    printf("Liczba %d jest większa od 5 \n",liczba);
  else 
    printf("Liczba %d jest mniejsza lub rowna 5 \n",liczba);
  return 0;
  
  ```
  
  
  Zad 2
  
```c
/*Wczyta liczbe calkowita i wypisze czy jest dodatnia,ujemna, czy rowna 0.*/

  int liczba;
  printf("Podaj liczbe \n");
  scanf("%d", &liczba);
  printf ("%d\n",liczba);
  if(liczba>0)
    printf("Liczba %d jest dodatnia \n",liczba);
  else if (liczba<0)
    printf("Liczba %d jest ujemna \n",liczba);
  else 
    printf("Liczba %d jest rowna 0 \n", liczba);
  return 0;
  ```
  
  Zad 3
  
```c
/*Wczyta liczbe calkowita i wypisze czy jest parzysta czy nieparzysta.*/
int n;
  printf("Wprowadz liczbe\n");
  scanf("%d", &n);
  printf ("%d\n",n);

  if(n%2==0)
  printf("Liczba %d jest parzysta\n",n);
  else
    printf("Liczba %d jest nieparzysta \n",n);
  return 0;
 ```

