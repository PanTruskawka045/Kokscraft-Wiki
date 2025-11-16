# Dlaczego nie wspieramy wersji 1.9 - 1.19.3?
Przy wejściu z tych wersji pojawia się ten komunikat, który nie pozwoli grać u nas na serwerze:

![komunikat-o-nie-wspieranej-wersji](/assets/bledy-dolaczania/komunikat-o-nie-wspieranej-wersji.png)

- Zdecydowaliśmy się wycofać wsparcie dla tych wersji z na prawdę wielu powodów. Nie będziemy wszystkich opisywać, poniżej wskazujemy na główne przyczyny:
1. Ilość osób korzystająca z tych wersji do skali błędów, jakie one powodowały, była nieopłacalna w dalszym wspieraniu. Wolimy się skupić na stabilnych wersjach gry, aby zapewnić uczciwą rozgrywkę.
2. Stałe błędy na niektórych wersjach, które są nie do naprawy i powodowały problemy w rozgrywce.

## Problem z AntiBotem

Jeżeli wyświetla się Tobie ten komunikat:

![komunikat-anti-bot](/assets/bledy-dolaczania/komunikat-anti-bot.png)

To sprawdź kilka sposobów, które niżej są opisane:
1. Spróbuj zresetować router.
2. Wejdź na czystej wersji Minecrafta bez jakichkolwiek modyfikacji np. vanilla, do tego najlepiej z wersji 1.8.9, 1.19.4+.
3. Spróbuj dołączyć za pomocą IP numerycznego 146.59.23.161:21040.
- Gdzie mam wpisać IP numeryczne, żeby mnie połączyło?
→ Otwórz launcher. 
→ Multiplayer.
→ Kliknij Direct Connect lub Add Server. 
→ W polu „Server Address” wpisz IP numeryczne. 
→ Połącz.
4. Spróbuj zmniejszyć "Odległość Renderowania" w ustawieniach graficznych Minecrafta, jeśli masz już ustawioną niską wartość np. (12) lub na najmniejszą możliwą wartość (2).
→ Wejdź w Start.
→ Ustawienia.
→ Sieć i Internet.
→ Wi-Fi.
→ Zmień opcje karty sieciowej.
→ Kliknij prawym przyciskiem na sieć (z której korzystasz).
→ Właściwości.
→ Zjedź w dół i wybierz Protokół internetowy w wersji 4 (TCP/IPv4).
→ Właściwości.
→ W preferowany serwer DNS wpisz: 208.67.222.222.
→ w alternatywny serwer DNS wpisz: 208.67.220.220.
→ Kliknij "OK" i zamknij wszystko oraz uruchom ponownie Minecrafta.

## Niełączenie z serwerem po zweryfikowaniu przez AntiBota
Jeżeli długo Ciebie łączy AntiBot, pomimo tego, że podświetla się na zielono jak na poniższym zrzucie ekranu, to:

![blad-z-polaczeniem-na-lobby](/assets/bledy-dolaczania/blad-z-polaczeniem-na-lobby.png)

1. Musisz poczekać na restart serwera, ponieważ administracja nic z tym nie może zrobić (najczęściej problem ustępuje w tym wypadku).
2. W każdej chwili możesz się dowiedzieć od administracji, kiedy był ostatni restart serwera.
3. Jeżeli dalej będziesz posiadał taki problem po restarcie serwera, to musisz skontaktować się z administracją, poprzez stworzenie ticketa na support.kokscraft.pl.

## Tworzenie kont przez VPN/PROXY zablokowane!

1. Na sam początek usuń wszystkie programy/aplikacje, które maskują Twoje IP.
2. Jeżeli jesteś z Polski i po zrobieniu pierwszego punktu dalej posiadasz taki problem, to może to oznaczać, że otrzymałeś IP z rotacji, które były używane do ataków. Narzędzia zewnętrzne oflagowały te IP jako niebezpieczne i może pomóc restart routera bądź kontakt z dostawcą internetu.
3. A jeżeli nie mieszkasz w Polsce to administracja/developerzy nie jest w stanie pomóc.

## Dostęp do zakładania kont został tymczasowo wyłączony 
Jeżeli wyświetla się Tobie ten komunikat:

![dostep-do-kont-zablokowany](/assets/bledy-dolaczania/dostep-do-kont-zablokowany.png)
 
Co oznacza ten komunikat?
- Dzieje się tak, gdy na Twoje IP jest stworzone X kont, które jest już u nas zarejestrowane na serwerze.
1. Musisz odczekać kilkanaście godzin i spróbować wejść ponownie. Administracja nie ma jak zdjąć tej blokady.

## NOT AUTHENTICATED WITH MINECRAFT.NET

1. Czasami serwery Mojangu są opóźnione bądź jest globalna awaria, przez co nie możesz wbić na serwer. W takim wypadku musisz odczekać jakiś czas.
- Tutaj masz linka do strony, gdzie możesz sprawdzić, czy faktycznie Mojang posiada awarie: https://downdetector.pl/status/minecraft/.

## Failed to login: the authentication servers are currently down for maintenace / Failed to login: Please switch to 'Mojang' mode to play with your original Account!

1. Jeżeli uruchamianie Minecrafta nie pomaga, to musisz:
- Po kliknięciu jednocześnie Win+R pokaże się takie okienko:

![Uruchomienie-folderu](/assets/bledy-dolaczania/uruchomienie-folderu.png)

→ W pustą luke obok "Otwórz:" wpisz "powershell -command "Start-Process notepad "$env:windir\system32\drivers\etc\hosts" -Verb runas".
→ Po wpisaniu kliknij "OK", ta czynność po chwili otworzy okno Windows PowerShell.
→ Zezwól aplikacji Notatnik, na wprowadzenie zmian klikając "Tak".
→ Usuń wszystkie linijki związane z Mojangiem oraz niezawierające znaku "#".
→ Następnie zapisz plik w lewym górnym rogu.
→ I uruchom ponownie Minecrafta.

- ![Plik-Windows-PowerShell](/assets/bledy-dolaczania/plik-windows-powershell.png)

## Invalid session
Jeżeli wyświetla się Tobie ten komunikat:

![invalid-session.png](/assets/bledy-dolaczania/invalid-session.png)

Co oznacza ten komunikat?
- Zazwyczaj oznacza to, że z konta non-premium próbujesz wejść pod nickiem, na którym jest przypisane konto premium.
1. Jeżeli posiadasz konto:
- non-premium, to spróbuj wbić pod innym nickiem.
- premium, to spróbuj włączyć gre ponownie. Jeżeli to nie pomoże, to zaloguj się na swoje konto od nowa.

## Błąd typu NULL

1. Wejdź na czystej wersji Minecrafta bez jakichkolwiek modyfikacji np. vanilla, do tego najlepiej z wersji 1.8.9, 1.19.4+.
2. Spróbuj dołączyć za pomocą IP numerycznego 146.59.23.161:21040.
- Gdzie mam wpisać IP numeryczne, żeby mnie połączyło?
→ Otwórz launcher.
→ Multiplayer.
→ Kliknij Direct Connect lub Add Server.
→ W polu „Server Address” wpisz IP numeryczne.
→ Połącz.
3. Jeżeli na innych serwerach też posiadasz taki problem, to może to oznaczać, że masz ustawiony zły wiek na koncie Microsoft, co wiąże się z zablokowaniem funkcji gry sieciowej.
4. Jeżeli występuje to tylko u nas, to już jest wina Twojego Minecrafta/komputera, a nie naszego serwera i musisz na własną rękę poszukać rozwiązania, ponieważ administracja nie będzie w stanie Tobie pomóc.

## Wystąpił błąd podczas tworzenia konta
Jeżeli wyświetla się Tobie ten komunikat:

![incognito-error.png](/assets/bledy-dolaczania/incognito-error.png)

Co oznacza ten komunikat?
- Oznacza to, że ktoś na naszym serwerze ustawił sobie incognito z takim samym nickiem co Ty, próbując wbić na serwer.
1. Musisz odczekać jakiś czas i wbić ponownie.
2. Jeżeli po dłuższym czasie dalej posiadasz taki problem, a posiadasz konto:
- premium to musisz kontaktować się poprzez stworzenie ticketa na support.kokscraft.pl.
- non-premium to musisz spróbować wejść pod innym nickiem.

## Wystąpił błąd podczas dołączania do serwera
Jeżeli wyświetla się Tobie ten komunikat:

![wystapil-blad-podczas-dolaczania](/assets/bledy-dolaczania/wystapil-blad-podczas-dolaczania.png)

1. Jeżeli jest to jednorazowy przypadek, to nie musisz się niczym przejmować, po prostu wbij ponownie na serwer.
2. Jeżeli ten komunikat pojawia się za każdym razem, kiedy próbujesz wbić na konkretny tryb, to stwórz ticketa na support.kokscraft.pl.

## Gracz o takim NICKU jest już na serwerze"
Jeżeli wyświetla się Tobie ten komunikat:

![gracz-o-podanym-nicku.png](/assets/bledy-dolaczania/gracz-o-podanym-nicku.png)

1. Spróbuj wyłączyć Minecrafta i uruchomić go ponownie.
2. Jeżeli po zrobieniu pierwszego punktu dalej nie możesz wejść na serwer to możliwe, że:
- ktoś gra aktualnie na serwerze zalogowany pod tym nickiem. W przypadku podejrzenia włamania warto stworzyć ticketa na support.kokscraft.pl.
- konto się zbugowało - powinno się naprawic w nocy przy restarcie lobby około 4:00.

## Wykryto nieprawidłowe zachowanie Twojego klienta
Jeżeli wyświetla się Tobie ten komunikat:

![wykryto-nieprawidlowe-zachowanie](/assets/bledy-dolaczania/wykryto-nieprawidlowe-zachowanie.png)

Co oznacza ten komunikat?
- Oznacza to, że nasz system AntiCheat wykrył u Ciebie podejrzane zachowanie, które może wskazywać na cheaty (niedozwolone mody), lagi lub winę Twojego klienta.
1. Jeżeli wyrzuciło Cię na trybach minigames niesłusznie, to nie jest możliwe przywrócenie żadnych statystyk.
2. Jeżeli posiadasz nagranie z sytuacji lub chciałbyś wiedzieć, co było przyczyną wyrzucenia z serwera, to stwórz ticketa na support.kokscraft.pl. Możliwe, że jeżeli wyrzuciło Ciebie niesłusznie, to dzięki zgłoszeniu błąd zostanie naprawiony lub dostaniesz wskazówki jak tego uniknąć.
3. Jeżeli dzieje się tak często, to prawdopodobnie będzie potrzebne Tobie nagranie z momentu otrzymania tego komunikatu (np. klip z [medala](https://medal.tv/), [NVIDIA ShadowPlay](https://www.nvidia.com/pl-pl/software/nvidia-app/)).