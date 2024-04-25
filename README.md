# Szkolenie z gita

## Instalacja

Windows: <https://git-scm.com/download/win>

## Podstawowe polecenia

### `git init`

Stworzenie nowego repozytorium w bieżącym katalogu.

**Uwaga! Najpierw należy założyć pusty katalog i wejść do niego**

```
mkdir moj_nowy_projekt
cd moj_nowy_projekt
git init
```

### `git status`

Sprawdzenie statusu zmian w bieżącym repo.

### `git diff`

Sprawdzenie zmian we wszystkich plikach.

Lub: `git diff plik.c` - tylko w jednym pliku.

Lub: `git diff *.cs` - tylko w plikach z rozszerzeniem `.cs`

Opcja `--word-diff` - pokazuje zmiany wewnątrz linii zamiast całych linii.

### `git commit`

Zatwierdzenie zmian.

- `git commit -m "Wiadomość"` - natychmiastowe zatwierdzenie, bez uruchamiania edytora

### `git config`

Konfiguracja gita. Należy wykonać ten krok jednorazowo przed pierwszym commitem.

```
git config --global user.name "Imię i Nazwisko"
git config --global user.email "imie.nazw@example.com"
```

## `tig`

Tig to pomocniczy program służący do przegladania historii gita. Jest domyślnie instalowany w pakiecie *Git for Windows*

### `tig nazwapliku.c`

Pokazuje historię danego pliku (tylko commity zmieniające ten plik)

### `tig blame nazwapliku.c`

Pokazuje kto i kiedy (w jakim commicie) dodał daną linię tekstu.

### `tig --all`

Pokazuje wszystkie dostępne gałęzie.
