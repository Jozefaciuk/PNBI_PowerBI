# Raport Przychodów Disney Movies (PNBI)

## Polecenie
Na podstawie zbioru danych Disney Movies opracuj raport na temat przychodów Disneya.

## Zbiór danych
Zbiór danych dotyczy wybranych filmów Disneya z lat 1937-2016.

### Opis kolumn:
* **Movie Title:** tytuł filmu,
* **Date Released:** data premiery,
* **Genre:** gatunek filmowy,
* **MPA Rating:** kategoria wiekowa rekomendowana przez Motion Picture Association,
* **Total Gross:** przychód z filmu,
* **Inflation Adjusted Gross:** przychód z filmu z uwzględnieniem inflacji[1].

*[1] Wartość umożliwiająca porównanie przychodów pomiędzy latami.*

---

## Ogólne zasady
* nie można modyfikować danych przed ich zaimportowaniem do programu Power BI,
* można modyfikować nazwy kolumn (w tym także dokonywać ich tłumaczenia),
* można tworzyć nowe miary, kolumny i tabele,
* można korzystać z wizualizacji niestandardowych,
* można dowolnie personalizować raport (w tym także zamieszczać grafiki).

---

## Wymagania funkcjonalne
1.  Raport powinien przedstawiać łączną liczbę filmów.
2.  Raport powinien przedstawiać łączny przychód z filmów.
3.  Raport powinien przedstawiać łączny przychód z filmów z uwzględnieniem inflacji.
4.  Raport powinien przedstawiać procentowy udział gatunków filmowych w łącznym przychodzie z filmów z uwzględnieniem inflacji[2].
5.  Raport powinien przedstawiać dziesięć filmów o największej różnicy pomiędzy przychodem z filmu z uwzględnieniem inflacji a przychodem z filmu posortowanych malejąco po tej różnicy[3].
6.  Raport powinien przedstawiać przychód z filmów i przychód z filmów z uwzględnieniem inflacji w kolejnych latach[4].
7.  Raport powinien umożliwiać jednoznaczną identyfikację filmu na podstawie jego tytułu[5].
8.  Raport powinien umożliwiać filtrowanie danych względem gatunku filmowego[6][7].
9.  Raport powinien umożliwiać filtrowanie danych względem kategorii wiekowej[6][7].
10. Raport powinien umożliwiać filtrowanie danych względem roku premiery[6].

### Przypisy do wymagań:
* **[2]** Wizualizacja nie powinna wyświetlać danych dla kategorii filmowej "Unknown".
* **[3]** Wizualizacja powinna wyświetlać także wartości kryterium sortowania.
* **[4]** Wizualizacja powinna graficznie obrazować różnicę pomiędzy tymi wartościami.
* **[5]** Jeżeli tytuł filmu nie jest unikatowym identyfikatorem, to na jego końcu należy zamieścić w nawiasie rok premiery (w innym przypadku nie).
* **[6]** Fragmentator powinien dopuszczać możliwość wyboru więcej niż jednej wartości jednocześnie.
* **[7]** Fragmentator nie powinien dopuszczać możliwości wyboru wartości "Unknown".

---

## Wymagania niefunkcjonalne
* Raport powinien składać się wyłącznie z jednej strony o domyślnym rozmiarze.
* Raport powinien zawierać nagłówek, który w jednoznaczny sposób będzie identyfikować jego treść.
* Raport powinien być czytelny i przejrzysty[8].
* Raport powinien być intuicyjny i łatwy w obsłudze[8].

*[8] Nie narzucam Państwu miar oceny tych kryteriów, ale zarówno UI, jak i UX również będą podlegać ocenie.*