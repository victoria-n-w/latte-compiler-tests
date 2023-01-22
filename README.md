# latte-compiler-tests

## Struktura

W katalogach `good` `bad` są testy, podzielone na kategorie:

 - arrays
 - basic
 - classes (struktury + metody)
 - structs
 - virtual methods
 
Testy mogą znajdować się w dowolnych podkatalogach. Jeśli test ma input/output, to w tym samym katalogu powinny znajdować się odpowiednio pliki `*.input`, `*.output`

## Użycie

żeby dostać testy z jakiegoś katalogu najlepiej imo używać `find`

```
find good/arrays -name "*.lat"
```
