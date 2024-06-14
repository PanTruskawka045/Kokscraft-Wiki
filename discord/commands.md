# Komendy
Komendy na Discordzie służą do interakcji z botami. 

## Legenda
- **/komenda** - komenda, którą wpisujemy na chacie. 
- **<argument>** - argument wymagany do poprawnego działania komendy.
- **[argument]** - argument opcjonalny, który nie jest wymagany do poprawnego działania komendy.
- **[argument1/argument2]** - argument wymagający wyboru jednej z dwóch (lub kilku) opcji.
- **[argument...]** - argument, który można powtórzyć wielokrotnie.

## Profile

### /profil [użytkownik] 
**[użytkownik]** - użytkownik, którego profil chcemy zobaczyć.

Wyświetla profil użytkownika.
Jeżeli argument nie zostanie podany, komenda wyświetli profil osoby ją wpisującej.

### /portfel [użytkownik]
Alisy: /balance  /money, /bal, /wallet
**[użytkownik]** - użytkownik, którego stan konta chcemy zobaczyć.

Wyświetla stan konta użytkownika.
Jeżeli argument nie zostanie podany, komenda wyświetli profil osoby ją wpisującej.

### /booster
Alisy:/boostery, /mnozniki 

Wyświetla aktualne boostery użytkownika. (Nie pokazuje sie boost z server boosta!)

### /rep [użytkownik]
Alisy: /reputacja, /reputation
**[użytkownik]** - użytkownik, któremu chcemy nadać punkt reputacji.

Nadaje punkt reputacji.

### /level [użytkownik]
Alisy: /lvl, /poziom, /rank
**[użytkownik]** - użytkownik, którego profil chcemy zobaczyć.

Wyświetla lvl użytkownika.
Jeżeli argument nie zostanie podany, komenda wyświetli profil osoby ją wpisującej.

### /ekwipunek [użytkownik] [strona]
Alisy: /eq, /inv, /inventory
**[użytkownik]** - użytkownik, którego profil chcemy zobaczyć.
**[strona]** - strona z ekwipunku, którą chcemy zobaczyć.

Wyświetla eq użytkownika.
Jeżeli argument nie zostanie podany, komenda wyświetli profil osoby ją wpisującej.

## Sklep

### /sklep [strona]
Alisy: /shop
**[strona]** - strona z sklepu, którą chcemy zobaczyć.

### /gift [przedmiot] [użytkownik]
Alisy: /kup-prezent, /prezent

**[przedmiot]** - przedmiot ze sklepu, który chcemu podarować.
**[użytkownik]** - użytkownik, któremu chcemy kupić prezent.

### /use 
Alisy: /uzyj

Pozwala wybrać przedmiot z ekwipunku, który chcemy użyc.

### /darmowa-zmiana-nicku 
Alisy: /odbierz-zmiane-nicku

Pozwala odebrać JEDNORAZOWĄ zmianę nicku.

## Topki

### /topka-coinsow [strona]
Alisy: /lb-coins, /leaderboard-coins, /coins-leaderboard, /topka-monet
**[strona]** - strona z topki monet, którą chcemy zobaczyć.

### /topka-expa 
Alisy: /leaderboard-xp, /lb-xp, /topka-xp, /xp-leaderboard 

Pokazuje link do strony na której są najlepsi użytkownicy według doświadczenia.

## Inne

### /odswiez-range
Alisy: /refresh-rank 

Odświeża range na discord, jeśli masz połaczone konto discord z minecraft'em i posiadasz rangę (bez rang limitowanych)

### /stats <gracz> [tryb]

**<gracz>** - nick użytkownika, którego chcemy sprawdzić statystki.
**[tryb]** - tryb z którego chcemy sprawdzić statystki (TntGames, SkyWars, HeadWars, TheBridge, UHC, BedWars)

Pokazuje statystki serwerowe gracza
