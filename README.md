# JFiTT

Zadania laboratoryjne w Javie.

## Zawartość

- [Laby1](Laby1) — wyszukiwanie wzorca w tekście za pomocą algorytmów FA i KMP.

## Wymagania

- Java 21, zgodnie z konfiguracją w `Laby1/pom.xml`.
- Maven do kompilacji projektu.

## Kompilacja i uruchomienie

Przejdź do katalogu laboratorium i skompiluj projekt:

```bash
cd Laby1
mvn compile
```

Uruchom wybrany algorytm, podając niepusty wzorzec i ścieżkę do pliku:
Ścieżki względne są liczone od katalogu, w którym uruchamiasz program.

```bash
java -cp target/classes pl.pattern.search.FA "<wzorzec>" "<ścieżka-do-pliku>"
java -cp target/classes pl.pattern.search.KMP "<wzorzec>" "<ścieżka-do-pliku>"
```

Program wypisuje pozycje znalezionych wystąpień, licząc indeksy od zera.
Implementacja FA używa tablicy przejść dla znaków ASCII.
