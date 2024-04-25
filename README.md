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

