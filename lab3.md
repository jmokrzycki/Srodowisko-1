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

Zad 4
```c
/*Sprawdzi czy liczby sa sobie rowne.*/
  int liczba,liczba2;
  printf("Podaj liczbe \n");
  scanf("%d",&liczba);
  printf ("Podaj druga liczbe \n");
  scanf("%d",&liczba2);

  if(liczba==liczba2) {
    printf("Liczba %d jest rowna liczbie %d\n",liczba,liczba2);
  }
  else {
    printf("Liczba %d nie jest rowna liczbie %d\n", liczba,liczba2);
  }
  return 0;
  ```
  Zad 5
  ```c
  /*Program, ktory wczyta 2 liczby calkowite i wypisze ktora z nich jest wieksza */


  int liczba,liczba2;
  printf("Podaj liczbe \n");
  scanf("%d",&liczba);
  printf ("Podaj druga liczbe \n");
  scanf("%d",&liczba2);

  if(liczba>liczba2) {
    printf("Liczba %d jest wieksza od liczby %d\n",liczba,liczba2);
  }

  else if(liczba==liczba2){
    printf("Liczba %d jest rowna liczbie %d\n",liczba,liczba2);
  }

  else {
    printf("Liczba %d jest mniejsza od liczby %d\n", liczba,liczba2);
  }
  return 0;
  ```
Zad 6
  ```c
/*Napisac program, ktory wczytuje liczbe calkowita n wieksze rowne 0, a nastepnie n liczb rzeczywistych 
(double %lf) i drukuje te liczby w trzech kolumnach w taki sposob, zeby zachowac krycie (
tzn. kropka dziesietna zawsze byla w tych samych kolumnach) np. gdy uzytkownik 
poda 7 0.12 -31.5 2.5 -59.01 26.4 -12.0 8.3 */

  int n;
  int i;
  printf("Podaj n:\n");
  scanf("%i",&n);
  //deklaracja tablicy
  double tab [n];
  //petla wczytujaca dane do tablicy, petla czyli for
  for (i=0;i<n;i++)
    scanf("%lf",&tab[i]);
  //petla wypisujaca dane z tablicy
  for(i=0;i<n;i++){
    printf("%2.5lf |",tab[i]);
  if(i%3==2)
    printf("\n");
  }
  //Mozna zakladac. ze liczby naleza do przedzialu (-100,100), zeby wydrukowal l.rzeczywista na 
  polu o dl. 6 znakow z 2 cyframi po kropce nalezy w komendzie printf uzyc formatu "%6.2lf". 
  komenda ./zad6 > plik_z_danymi wpiszemy wartosci w pliku, a 
  komenda ./zad6 <plik_z_danymi otwieramy program przy wykorzystaniu danych z pliku
```


