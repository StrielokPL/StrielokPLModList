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
przez nazwę zakładki. Repozytoria editów są aktywnymi wpisami na oficjalnej liście:

- https://github.com/StrielokPL/Edit330Miziuu
- https://github.com/StrielokPL/Edit355360Miziuu

**Wymagają updatera 0.0.1a15 lub nowszego.** Starszy updater 0.0.1a14 odrzuca
listę z tymi aktywnymi wpisami i zachowuje ostatnią poprawnie wczytaną listę.

Edity zawierają tylko zmienione pliki. Pobierz oryginał autora przyciskiem
„Pobierz zalecaną bazę z ModsFire”, a następnie wybierz
„Zainstaluj edit na oryginalnym ZIP-ie…”. Można użyć także oryginału już obecnego
w folderze modów. Updater sprawdza zgodność i prosi o potwierdzenie przy innej
bazie, a następnie pozwala wybrać wykonanie kopii poprzedniego moda.
Jeżeli zachowano kopię oryginału, można go przywrócić z listy wersji editu.

Linki informacyjne do innych serwisów należy zapisywać jako komentarze.
