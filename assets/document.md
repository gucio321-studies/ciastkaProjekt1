# Rysowanie komórki elementarnej

Pobrano plik `.cif` z bazy COD (Crystallography Open Database) o ID: 1011169.
Niestety program PowderCell w wersji 2.4 nie oferuje możliwości importu plików `.cif`, dlatego parametry sieci należy
wpisać manualnie.

```{figure} import_tabeli.png
Ustawienia importu do programu PowderCell.
```

W ten otrzymano następująćą komórkę elementarną:

```{figure} el_cell1.png
:scale: 50%
:latex: float=H

Komórka elementarna w rzucie z góry
```

```{figure} el_cell2.png
:scale: 50%

Komórka elementarna w rzucie z boku
```

```{raw} latex
\pagebreak
```

# Oś główna

Ustawiono komórkę elementarną wzdłóż osi głównej pokrywającej się z osią c.
Osiągnięto symetrię poczwórną przy obrocie o $90^\circ$.

```{figure} os_obrotu.png
:scale: 50%

4-krotna oś symetrii
```

# Warunki wygaszeń systematyczych w grupie Fm-3m

Związek `FeO` należy do grupy przestrzennej nr 225 (Fm-3m).
Ta grupa posiada następujące warunki **odbicia**:

```{figure} reflection_conditions.png
Warunki odbicia
```

Co przekłada się na następujące warunki **wygaszeń systematycznych**:

```
HKL :    H+K,H+L,K+L=2n+1
0KL :    K=2n+1, L=2n+1
H0L :    H=2n+1, L=2n+1
HK0 :    H=2n+1, K=2n+1
HHL :    H+L=2n+1
HKH :    H+K=2n+1
HKK :    H+K=2n+1
H00 :    H=2n+1
0K0 :    K=2n+1
00L :    L=2n+1
0KK :    K=2n+1
H0H :    H=2n+1
HH0 :    H=2n+1
```

# Dyfrakcja

Wykonano symulację dyfrakcji rentgenowskiej zgodnie z parametrami zadania:
- Lampa Cu $k_\alpha$,
- Kąt 2$\Theta$ od $10^\circ$ do $80^\circ$,

```{figure} dyfrakcja.png
Dyfraktogram uzyskany w programie PowderCell na sieci FeO.
```

```{raw} latex
\pagebreak
```

# Odległosći żelaza i tlenu


```{figure} bond_length.png
Długość wiązania Fe-O w sieci krystalicznej FeO.
```



# Odległośc między płaszczyznami

Odczytano następujące wartośći odległości dla poszczególnych rodzin płaszczyzn:

```{figure} hkl.png
Odległości między płaszczyznami dla różnych rodzin (hkl).
```

Dla rodziny płaszczyzn (200), suma $h+k+l = 2$ jest najmniejsza,
stąd $d_{200} = 2.166$.

# Literatura

- https://www.crystallography.net/cod/result.php ID: 1011169 Dostęp: 2025-11-26
- http://img.chem.ucl.ac.uk/sgp/large/225az1.htm
