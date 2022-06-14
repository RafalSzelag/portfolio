
id | Wymaganie w oparciu o specyfikację
---|---
1|MrBuggy 3 ma być aplikacją przenośną, która ma być dostarczona w postaci archiwum “zip”. Rozpakowane archiwum musi zawierać plik wykonawczy, który uruchamia aplikację oraz wszystkie niezbędne biblioteki i zasoby.
2|W trybie członka drużyny możliwość raportowania defektów jest zablokowana.
3|Aplikacja kliencka musi pracować w jednym z trzech trybów. Tryb pracy należy wybrać w trakcie logowania do aplikacji.
4|Zmiana trybu pracy w trakcie działania aplikacji jest niemożliwa.
5|Okno aplikacji powinno mieścić się w całości na ekranie monitora o rozdzielczości 1024x768.
6|Wersja demonstracyjna powinna zawierać tylko jedno zadanie testowe.
7|Wśród zadań zamieszczonych w wersji końcowej nie może się znaleźć zadanie z wersji demonstracyjnej.
8|Aplikacja musi posiadać możliwość ręcznego importu oraz eksportu danych
9|Aplikacja ma za zadanie generować dziennik zdarzeń w wersji klienckiej.
10|Wersja kliencka ma zawierać nie mniej niż 15 zadań.
11|Hasło logowania musi składać się z co najmniej 8 znaków.
12|Aplikacja musi być napisana w języku polskim 
13|Każde zadanie musi zawierać przynajmniej jeden defekt.
14|Defekty w zadaniach mogą należeć do grup defektów funkcjonalnych albo defektów bezpieczeństwa.
15|Wszystkie zadania muszą zostać zaimplementowane w aplikacji.
16|Aplikacja w wersji klienckiej musi umożliwiać użytkownikowi poszukiwanie jednego defektu w każdym z zadań oraz ich raportowanie.
17|Aplikacja musi wyświetlać listę zadań oraz przyciski nawigacyjne.
18|Zadania na liście muszą być oznaczane różnymi kolorami w zależności od ich statusu (aktualnie wyświetlane, rozwiązane, nierozwiązane).
19|Po kliknięciu przycisku "Zgłaszam defekt" aplikacja musi automatycznie tworzyć plik z kopią zapasową.
20|Okno aplikacji powinno dzielić się na dwie części - okno “Zadania” oraz “Menu boczne” ułożone po prawej stronie.
21|Przyciski nawigacyjne “Następne” i “Poprzednie” umożliwiają przeniesienie się do odpowiednio następnego i poprzedniego zadania.
22|Część kliencka musi działać na systemach Windows 7 oraz Windows 8/8.1, a część serwerowa na systemie Windows 7.
23|Kopia zapasowa ma być tworzona po każdorazowym kliknięciu w przycisk “Znalazłem defekt”.
24|Konto powinno zostać zablokowane po 3 krotnym wpisaniu błędnego hasła.
25|Przełączanie pomiędzy zadaniami nie może trwać dłużej niż 1 sekunda.
26|Aplikacja kliencka po uruchomieniu nie może zajmować więcej niż 100MB pamięci operacyjnej komputera.
27|Wielkość pliku z kopią zapasową aplikacji klienckiej nie może przekraczać 2MB.
28|W oknie “Zadania” powinno wyświetlać się zadanie, w którym użytkownik ma odnaleźć defekt.
29|W przypadku utraty połączenia sieciowego użytkownik powinien mieć dalszą możliwość wykonywania wszystkich czynności w aplikacji.
30|Kolejność zadań wyświetlanych w części klienckiej powinna być losowa.
31|Pole “Czas” powinno wyświetlać czas do zakończenia rundy w formacie: gg:mm:ss:ms; godzina, minuta, sekunda, milisekunda).
32|Pole “Nr zadania” - powinno wyświetlać numer zadania wyświetlonego w oknie “Zadania”.
33|Pole “Opis problemu” powinno zawierać ogólną informację na temat zadania wyświetlonego w polu “Zadania” wraz z ilością punktów za dane zadanie.
34|Pole “Lista zadań” powinno umożliwiać nawigację pomiędzy zadaniami.
35|"Przycisk “Zaraportuj defekt” powinien pozwalać na zaraportowanie defektu aktualnie wyświetlanego w oknie “Zadania”.
36|Przycisk “Zakończ” powinien pozwalać na zakończenie pracy nad wszystkimi zadaniami i wysłanie odpowiedzi do oceny. Czynności tej nie można cofnąć i wykoać ją można tylko jeden raz. Aby uniknąć pomyłek użytkownik powinien potwierdzić chęć wykonania tej czynności. Po wciśnięciu przycisku “Zakończ” wszystkie dane dotyczące użytkownika oraz rozwiązanych przez niego zadań testowych powinny zostać wyeksportowane  do pliku binarnego. 
