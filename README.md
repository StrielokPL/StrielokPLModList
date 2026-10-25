# StrielokPL — lista modów

Plik `mods.txt` jest wczytywany przez Strelok FS25 Mod Updater jako osobna zakładka.

## Edycja listy

1. Otwórz `mods.txt` i wybierz edycję (ołówek).
2. Pierwszy wiersz to nazwa zakładki.
3. Wklej każdy nowy link w osobnym wierszu.
4. Zapisz zmiany przyciskiem Commit changes.

Obsługiwane linki: strony modów FS25 na KingMods i strony plików ModsFire,
wyłącznie przez HTTPS. Puste wiersze i komentarze zaczynające się od `#` są pomijane.

```text
StrielokPL
https://www.kingmods.net/en/fs25/mods/63913/ursus-c-330330m
# Tutaj można wkleić kolejny link KingMods lub ModsFire.
```

W aplikacji wybierz **Opcje → Dodaj paczkę z GitHuba…** i wklej adres tego repozytorium.
Można też pobrać `mods.txt` i wybrać **Wczytaj plik jako zakładkę…**.
Każda lista ma osobną zakładkę. Zapisana lista GitHub jest sprawdzana co 15 minut.

Link ModsFire otwiera stronę pobrania. Sam adres ModsFire nie określa numeru wersji;
aplikacja odczyta wersję z pobranego ZIP-a. KingMods udostępnia wybór wersji.

Ta oficjalna lista ma dodatkowe uprawnienie do wskazywania repozytorium
`StrielokPL/Ursus16541954`. Obce listy i pliki lokalne nie otrzymują tego uprawnienia
przez nazwę zakładki. Repozytoria nowych editów zapisano w `mods.txt` jako komentarze:

- https://github.com/StrielokPL/Edit330Miziuu
- https://github.com/StrielokPL/Edit355360Miziuu

Zawierają tylko zmienione pliki. Updater 0.0.1a14 odczytuje ich metadane zgodności,
ale nie instaluje jeszcze tych paczek jako nakładek na oryginalny ZIP. Dlatego nie
należy usuwać znaków `#` przy tych adresach przed dodaniem ich obsługi w aplikacji:
nieobsługiwany aktywny adres powoduje odrzucenie odświeżanej listy.
Linki informacyjne do innych serwisów również należy zapisywać jako komentarze.
