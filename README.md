# Zasady ogólne

1. Pamiętaj o ortografii
2. Używaj polskich znaków
3. Pamiętaj o interpunkcji
4. Nie edytuj plików w folderze `Administracyjne`

# Minigry i tryby survival

Zacznij od nagłówka stopnia 1, w którym będzie nazwa trybu (w tym przykładzie: bedwars)
Poniżej opisz w 3-5 zdaniach co to jest za tryb i co się na nim robi

```md
# Bedwars

Tryb polega na budowaniu bazy, zbieraniu zasobów i eliminowaniu innych graczy
```

Następnie dodawaj nagłówki stopnia 2, które będą opisywały dane części gry

```md
## Generator

Generator to miejsce, w którym zbieramy zasoby
![Generator Bedwars](/assets/bedwars/example-generator.png)
```

# Obrazki

Obrazki dodawaj do folderu 'assets' w odpowiednim folderze (np. bedwars) i odwołuj się do nich w pliku w poniższy
sposób:

Załóżmy że na obrazku jest generator i opisujesz tryb bedwars.
Plik umieść w folderze `assets/bedwars`, i nazwij go tak, żeby nazwa ukazywała co dany obrazek przedstawia
W tym przykładzie plik z obrazem nazywa się `example-generator.png`
Aby Umieścić obrazek w artykule, użyj poniższego kodu:

```md
![Generator Bedwars](/assets/bedwars/example-generator.png)
```

W kwadratowych nawiasach podaj opis obrazka, a w nawiasach okrągłych ścieżkę do obrazka (jak na przykładzie)

# Tabelki

Przykładowa tabelka:

```md

| **a**   | **b**   | **c**   | **d**   | **e**   |
|---------|---------|---------|---------|---------|
| 1       | 2       | 3       | 4       | 5       |
| 6       | 7       | 8       | 9       | 10      |
```

| **a** | **b** | **c** | **d** | **e** |
|-------|-------|-------|-------|-------|
| 1     | 2     | 3     | 4     | 5     |
| 6     | 7     | 8     | 9     | 10    |

# Formatowanie tekstu

Jeśli chcesz **pogrubiać** tekst, użyj podwójnych gwiazdek:

```md
**pogrubiony tekst**
```

Jeśli chcesz *kursywować* tekst, użyj pojedynczych gwiazdek:

```md
*kursywa*
```

Jeśli chcesz ~~przekreślić~~ tekst, użyj podwójnych tyld:

```md
~~przekreślony tekst~~
```

# Formatowanie tekstu Minecraft

Wiki obsługuje specjalną składnię do renderowania tekstu wyglądającego jak w grze Minecraft (czat/MOTD). System
obsługuje **Legacy Color Codes** (używając znaku `&`).
Tekst wewnątrz tagu zostanie wyrenderowany na ciemnym tle (styl czatu) z odpowiednią czcionką i kolorami.

### Składnia

Aby użyć kolorów, zamknij tekst w bloku `[MINECRAFT: ... ]`.

```md
[MINECRAFT:&cTo jest czerwony tekst &ai zielony.]
```

### Dostępne kody

| Kod | Kolor / Efekt   |
|-----|-----------------|
| &0  | Czarny          |
| &1  | Ciemnoniebieski |
| &2  | Ciemnozielony   |
| &3  | Ciemnoturkusowy |
| &4  | Ciemnoczerwony  |
| &5  | Ciemnofioletowy |
| &6  | Złoty           |
| &7  | Jasnoszary      |
| &8  | Ciemnoszary     |
| &9  | Niebieski       |
| &a  | Zielony         |
| &b  | Turkusowy       |
| &c  | Czerwony        |
| &d  | Fioletowy       |
| &e  | Żółty           |
| &f  | Biały           |
| &k  | Magiczny        |
| &l  | Pogrubiony      |
| &m  | Przekreślony    |
| &n  | Podkreślony     |
| &o  | Kursywa         |
| &r  | Reset           |

### Przykłady użycia

`Wiadomość o banie:`
[MINECRAFT:&cGracz &4Admin &czbanował &eNoobka&c.]

# Badge

Możesz dodawać stylowe odznaki, aby oznaczać rangi, statusy lub wersje.
Składnia: `[badge:TEKST:KOLOR]`

* Rangi: [badge:VIP:orange], [badge:ADMIN:red], [badge:GRACZ:gray]
* Statusy: [badge:BETA:blue], [badge:NOWOŚĆ:green], [badge:WIP:yellow]
* Inne: [badge:1.20.4:primary]

Przykłady użycia w tekście:

Ta komenda jest dostępna tylko dla rangi [badge:MVP:indigo] i wyższych.
Funkcja działek jest obecnie w fazie [badge:BETA:red].

Dostępne kolory:
`red, green, blue, yellow, orange, indigo, purple, gray, primary`

# Ramki

Zamiast zwykłego tekstu, używaj specjalnych bloków, aby wyróżnić ważne informacje.

> [!NOTE]
> Pamiętaj, że ranga VIP wygasa po 30 dniach.

```md
> [!NOTE]
> Pamiętaj, że ranga VIP wygasa po 30 dniach.
```

> [!TIP]
> Użyj komendy /msg, aby napisać prywatną wiadomość.

```md
> [!TIP]
> Użyj komendy /msg, aby napisać prywatną wiadomość.
```

> [!IMPORTANT]
> Nie udostępniaj swojego hasła innym osobom.

```md
> [!IMPORTANT]
> Nie udostępniaj swojego hasła innym osobom.
```

> [!WARNING]
> Wchodząc na arenę PvP tracisz ochronę ekwipunku!

```md
> [!WARNING]
> Wchodząc na arenę PvP tracisz ochronę ekwipunku!
```

> [!CAUTION]
> Usunięcie działki jest nieodwracalne.

```md
> [!CAUTION]
> Usunięcie działki jest nieodwracalne.
```

# Linki

Jeśli chcesz dodać link do strony, użyj poniższego kodu:

```md
[tekst linku](adres linku)
```

(Używaj komentarzy tylko wtedy, gdy jest to konieczne, np. gdy chcesz coś wyjaśnić, ale nie chcesz, żeby to było
widoczne na stronie)

```md
Kolory
```

Przykład jak dodać kolory poniżej:

[slate/]Slate[/slate] - `[slate/]Slate[/slate]`
[gray/]Gray[/gray] - `[gray/]Gray[/gray]`
[zinc/]Zinc[/zinc] - `[zinc/]Zinc[/zinc]`
[neutral/]Neutral[/neutral] - `[neutral/]Neutral[/neutral]`
[stone/]Stone[/stone] - `[stone/]Stone[/stone]`
[red/]Czerwony[/red] - `[red/]Czerwony[/red]`
[orange/]Pomarańczowy[/orange] - `[orange/]Pomarańczowy[/orange]`
[amber/]Bursztynowy[/amber] - `[amber/]Bursztynowy[/amber]`
[yellow/]Żółty[/yellow] - `[yellow/]Żółty[/yellow]`
[lime/]Limonkowy[/lime] - `[lime/]Limonkowy[/lime]`
[green/]Zielony[/green] - `[green/]Zielony[/green]`
[emerald/]Szmaragdowy[/emerald] - `[emerald/]Szmaragdowy[/emerald]`
[teal/]Teal[/teal] - `[teal/]Teal[/teal]`
[cyan/]Cyjan[/cyan] - `[cyan/]Cyjan[/cyan]`
[sky/]Sky[/sky] - `[sky/]Sky[/sky]`
[blue/]Niebieski[/blue] - `[blue/]Niebieski[/blue]`
[indigo/]Indigo[/indigo] - `[indigo/]Indigo[/indigo]`
[violet/]Fioletowy[/violet] - `[violet/]Fioletowy[/violet]`
[purple/]Purpurowy[/purple] - `[purple/]Purpurowy[/purple]`
[fuchsia/]Fuksja[/fuchsia] - `[fuchsia/]Fuksja[/fuchsia]`
[pink/]Różowy[/pink] - `[pink/]Różowy[/pink]`
[rose/]Róża[/rose] - `[rose/]Róża[/rose]`

# Pull Request

Zmiany wrzucaj w pull request'ach.
Jedna zmiana = jeden pull request.
W opisie pull requesta napisz:

1. Swój nick w minecraft
2. Co mniej więcej zmieniłeś


