### curs-04-demo


1. Laborator 1, exercițiu 5, mem.c 
   - se printează octet cu octet conținutul fiecărei variabile
   - observați adresele de început pentru variabile
   - observati adresele fiecărui octet component
   - reconstituiți valoarea variabilei folosind octeții si aritmetica în baza 16
   
2. endian.asm
   - compilați si încărcati în gdb
`make
 gdb endian
 b main
 r`
   - examinați variabilele a, b, c
   - octet cu octet cu comanda în gdb:  x/20xb &a
   - short cu short cu comanda în gdb:  x/20xh &a
   - word cu word cu comanda în gdb:  x/20xw &a
   - idem pentru variabilele b, c


3. mem.c 
   - se printează în C conținutul variabilelor octet cu octet 
   - se verifică și în gdb 
   
4. bin-oct-hex.c
   - baza 8, sau "capcanele C-ului"
   
   



