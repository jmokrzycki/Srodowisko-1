# Rozwiązania zadania LAB 2

Zad 1

```c
/*Napisać i uruchomić program w C, który wczytuje liczbę naturalną n i drukuje
wartość sumy kwadratów 1^2+2^2+....+n^2. */
main()
{
  int x,n,kwadrat;
  int suma=0;
  printf("Podaj liczbę\n");
  scanf("%i",&n);
 
  for (x=0; x<=n;x++){
   kwadrat=x*x;
   
   suma=suma+kwadrat;
  }
    printf("Wartość sumy kwadratów wynosi %i\n",suma); 
}
```

Zad 2
```c
/*Napisać program obliczający wartość każdego z poniższych wyrażen: 
n1=5+3*8/2-3
n2=2%2+2*2-2/2
n3=2*4*(5+9/2)*/

main(){
  int n1,n2,n3;

  n1=5+3*8/2-3;
  n2=2%2+2*2-2/2;
  n3=2*4*(5+9/2);

  printf("Wynik działania to %i\n %i\n %i\n", n1, n2, n3);
    }
```

Zad 3

```c
/*W miejsce kropek "...." wpisz kod tak, aby powstał działający program. 
Program wypisuje liczby z tablicy tabela [] w odwrotnej kolejności, tj. 12,6,4,2,1.*/

int main() {
int i;
int tabela[]={1,2,4,6,12};
for(i=4;i=>0;i=i-1)
printf("%i",tabela[i]);
return 0;
}
```
