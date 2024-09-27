# 11 Arrays
## 11.9 Daglige Differencer
Skriv et program, der givet 7 dagstemperaturer udregner og udskriver temperaturdifferencen mellem alle 
to på hinanden følgende dage (dvs. Tirsdag-Mandag, Onsdag-Tirsdag . . . Søndag-Lørdag).

Dagstemperaturerne kunne være:
* Mandag 21.5
* Tirsdag 23.7
* Onsdag: 19.6
* Torsdag: 22.5
* Fredag: 25.3
* Lørdag: 21.7
* Søndag: 18.9

**Bemærk :** Dette er en gentagelse af øvelse 10.4. 
I mellemtiden har vi dog fået nye (og bedre egnede) værktøjer til at løse den.

# 14 Funktioner
## 14.3 Soduku Prettyprinter
Følgende datastruktur repræsenterer en udfyldt sudoku plade:

    int[][] puzzle = new int[][] {
    
        new int[]{7, 3, 6, 4, 5, 2, 9, 8, 1},
        new int[]{1, 9, 8, 6, 3, 7, 4, 5, 2},
        new int[]{4, 2, 5, 9, 8, 1, 3, 7, 6},
        new int[]{3, 6, 4, 5, 2, 8, 1, 9, 7},
        new int[]{9, 5, 2, 7, 1, 4, 6, 3, 8},
        new int[]{8, 1, 7, 3, 9, 6, 2, 4, 5},
        new int[]{2, 8, 9, 1, 7, 3, 5, 6, 4},
        new int[]{6, 7, 3, 2, 4, 5, 8, 1, 9},
        new int[]{5, 4, 1, 8, 6, 9, 7, 2, 3},
    };

Skriv et program, hvori
1. Ovenstående datastruktur er defineret.
2. En metode er defineret der som parameter tager en sådan struktur og skriver den ud på skærmen.
   * Hvilken prototype (i.e., returværdi og signatur) skal denne metode have?
   * Skal man udprinte en række af gangen eller en søjle af gangen?
   * **Hint:** Metoden Console.Write gør det samme som Console.WriteLine men undlader at bryde linjen.
3. Noget kode kalder denne metode.
## 14.4 Sum
Skriv en metode, der lægger to heltal sammen. 
Skriv derudover en main metode der viser hvordan denne metode skal bruges.
## 14.5 Egen Kvadratrod
Skriv et program, hvori
1. En metode kaldet sqrt kan kaldes for at udregne kvadratroden af en double med fx 7 decimale cifre.
   * **Hint:** Prøv jer frem for hvert ciffer, og brug et loop til at iterere over cifrene 1000000000 til 0.000000001. 
   Hvad skal værdien af dette ciffer være? Når I har fundet den bedste værdi fortsætter I til det næste. 
   Den bedste værdi er den der (når den lægges sammen med de tidligere fundne bedste værdier) er ≤ kvadratroden af input. 
   På denne måde vil I løbende komme flere og flere betydende cifre på, og dermed nærme jer det perfekte svar.
2. Der er noget kode som demonstrerer brugen af denne metode.
## 14.8 Fakultet
Skriv et program, hvori
1. En metode udregner fakultet18 (e.g., fac(4) = 4 · 3 · 2 · 1) uden brug af et loop.
   * **Hint:** Dette kan gøres ved hjælp af rekursion.
2. Noget kode kalder denne metode og udskriver resultatet.
## 14.9 Cirkler i Tal
Skriv et program der udregner og udskriver både arealet (π · r2) og omkredsen (2 · π · r) af tre cirkler med radius på hhv. 1, 3 og 5.

**Bemærk:** Dette er en gentagelse af øvelse 11.8. 
I mellemtiden har vi dog fået nye (og bedre egnede) værktøjer til at løse den.