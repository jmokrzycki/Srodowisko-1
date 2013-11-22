```c

Zad 3
/*Ile jest planet w układzie słonecznym?*/
$7=="Planet" {p++}
END {print "Planet w ukladzie slonecznym jest:",p}


Zad 4
/*Jaka jest suma objetosci cial o regularnym ksztalcie? */ 
$8 == "regular" {p=p+$3} END {print "Suma objetosci cial o regularnym ksztalcie wynosi:",p}   

Zad 5
/*Wypisz planety z układu słonecznego w następujący sposób: np. NAZWA_PLANETY jest planeta o
masie MASA*10^21kg oraz objętości OBJETOSC*10^9km^3. */

$7 =="Planet" {print $1 " jest planeta o masie "$4"*10^21kg oraz objetosci "$3"*10^9km^3."}

Zad 6
/*Znajdź satelite Saturna o najmniejszej masie*/

$7=="Satellite-Saturn"  {if (i<$4);(i=$4)} 

END {print i}

Zad 7
/*Znajdz satelite Saturna o najwiekszej objetosci*/

$7=="Satellite-Saturn"  {if (i<$3){i=$3}} 
END {print i}
