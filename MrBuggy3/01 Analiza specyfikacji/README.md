Strona w specyfikacji, gdzie wystąpił błąd|Opis błędu
---|---
5, 13|W spisie definicji opisano instalator aplikacji, podczas gdy Mr Buggy 3 ma być aplikacją przenośną, bez instalatora.
6|Wymagane są cztery wersje aplikacji klienckiej - w treści wymienione są tylko trzy.
7|"Język programowania oraz baza danych **urzyta** podczas tworzenia aplikacji nie są zdefiniowane" podczas gdy dalej wskazano, że "Aplikacja serwerowa ma zostać stworzona przy wykorzystaniu języka Java7" (ponadto w zdaniu znajduje się błąd ortograficzny).
7|Nie określono czy wymagane środowisko ma być w wersji 32 czy 64 bitowej.
7, 11|Sprzeczność w zakresie rodzaju pliku - "Dane z części klienckiej dostarczane są do części serwerowej w postaci pliku tekstowego" - "Po wciśnięciu przycisku “Zakończ” wszystkie dane dotyczące użytkownika oraz rozwiązanych przez niego zadań testowych eksportowane do pliku binarnego."
8|Kategoryzując rodzaje defektów nie ma potrzeby rozróżniania defektów funkcjonalnych i defektów użyteczności gdyż są to pojęcia tożsame.
8|W specyfikacji wskazano, że w aplikacji ma znaleźć się nie mniej niż 15 zadań, podczas lista zadań na schemacie aplikacji nie zawiera miejsca na tyle pól.
8, 10|W opisie przycisku "Zaraportuj defekt" wskazano, że "Funkcja ta jest dostępna we wszystkich trybach pracy aplikacji.", chociaż ustalono wcześniej, że użytkownik w trybie członka drużyny nie może korzystac z funkcji raportowania defektów.
9|Brak szczegółowego opisu procesu raportowania defektów przez zawodników, przez co niemożliwe jest zaplanowanie funkcjonalności automatycznej oceny zadań przesłanych przez zawodników.
9|"Kolejność zadań wyświetlanych w części klienckiej powinna być losowa" - brak uszczegółowienia, jak miałoby to działać w trybie drużynowym.
10|"Pole “Czas” - wyświetla czas do zakończenia rundy (format: gg:mm:ss; godzina, minuta, sekunda, milisekunda)" - brak milisekund w formacie: gg:mm:ss:ms.
10|Funkcjonalność przycisków "Zakończ" i "Zaraportuj defekt" dublują się. Skoro przycisk "Zaraportuj defekt" powoduje wysłanie raportu do części serwerowej, to przesłanie raportu po kliknięciu przycisku "Zakończ" nie wydaje się potrzebne. 
10|Wartości brzegowe w punktacji za znalezione defekty normalne (od 3 do 4 pkt) oraz defekty krytyczne (od 4 do 6 pkt) pokrywają się.
10|Niejasny opis funkcjonalnośći przycisku "Zakończ". Z opisu wynika, że po wciśnięciu tego przycisku należy potwierdzić operację, jednoczesnie wskazując, że kliknięcie przycisku "Zakończ" następuje eksport danych. Trzeba zatem dookreślić, w którym momencie następuje eksport danych i jak ma wyglądać potwierdzenie operacji.
10|Opis działania przycisku "Zaraportuj defekt" wydaje się być niepełny, nie określono bowiem sposobu opisu defektu. Przesłanie raportu w chwili kliknięcia przycisku wydaje się przedwczesne.
10|Opis przycisków nawigacyjnych jest błędny, gdyż nie umożliwią one przeniesienia się do bieżącego zadania, a jedynie następnego albo poprzedniego.
10|W opisie pola "Nr zadania" wskazano, że "zasady numeracji zadań są opisane poniżej" - w specyfikacji brak opisu zasad numeracji.
10, 11|Na lilście elementów menu jest opisany przycisk "Zaraportuj defekt", a na schemacie aplikacji znajduje się przycisk “Znalazłem defekt”.
10, 11|W specyfikacji opoisano pole “Opis problemu” podczas gdy na schemacie jest pole "Opis zadania".
11|Na schemacie aplikacji znajduje się pole "Status połączenia", które nie jest opisane w specyfikacji.
11|Na schemacie aplikacji brak wyszczczególnionego miejsca na ikonę programu, chociaż jest to element wymagany.
12|"login musi składać się z 2 do 8 znaków i zawierać przynajmniej jedną małą literę, jedną wielką literę, jedną cyfrę i jeden znak specjalny" – sprzeczość w wymaganiu, gdyż aby spełnić kryteria login musi składać się z minimum czterch znaków.
12|"hasło musi składać się z co najmniej 20 znaków" -biorąc pod uwagę charakter aplikacji wymaganie to wydaje się przesadzone. 
12|Wielkość pliku z kopią zapasową określono na maksymalnie 2MB1 - nie jest jasne czy chodzi o 2MB czy 21MB, lub jeszcze inny rozmiar.
13|"konto musi zostać zablokowane po 3 krotnym wpisaniu błędnego hasła lub jego części" - niepotrzebny dopisek "lub jego części", gdyż w obu przypadkach warunek zostaje spełnion.y
13|"przełączanie pomiędzy zadaniami nie może być dłuższe niż 1 sekunda" - jest to wymaganie wydajnościowe, błędnie opisane w specyfikacji jako wymaganie niezawodności.
