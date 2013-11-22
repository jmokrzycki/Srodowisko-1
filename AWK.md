```awk
/*6. Znajdź satelite Saturna o najmniejszej masie*/

$7=="Satellite-Saturn"  {if (i<$4);(i=$4)} 

END {print i}

```
