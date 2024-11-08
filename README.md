                        Zadanie: Baza filmów

Opis zadania: 
	>Zadanie polega na analizie bazy danych filmów oraz gatunków, z wykorzystaniem bibliotek pandas oraz matplotlib w języku Python. Wykonujemy szereg kroków, aby uzyskać odpowiedzi na 	pytania oraz zwizualizować wyniki.

Wymagane dane:
 	>Baza filmów (tmdb_movies.csv): Zawiera informacje o filmach, takie jak średnia ocena, liczba głosów, czas trwania, przychód, budżet oraz identyfikator gatunku (genre_id). 
	>Baza gatunków (tmdb_genres.csv): Zawiera informacje o nazwach gatunków wraz z ich identyfikatorami.

Cele zadania: 
	>Top 10 najwyżej ocenianych filmów 
	>Zwróć listę 10 filmów z najwyższą średnią oceną (vote_average), które mają liczbę głosów (vote_count) większą niż 3. kwartyl rozkładu liczby głosów.
	>Średni przychód i budżet w latach 2010-2016 
	>Pogrupuj filmy według lat wydania i oblicz średni przychód (revenue) oraz średni budżet (budget) dla filmów opublikowanych od 2010 do 2016 roku. Na podstawie wyników stwórz wykres, 	na którym: średnie przychody są przedstawione jako wykres kolumnowy, Średni budżet jest przedstawiony linią na tych samych osiach. Sformatuj oś X oraz Y, dodaj tytuł oraz legendę 	umieszczoną w prawym górnym rogu poza obszarem osi.
	>Łączenie tabel: Połącz bazę filmów z bazą gatunków na podstawie kolumny genre_id, aby móc odczytać nazwę gatunku filmu bezpośrednio w bazie filmów.
	>Najczęściej występujący gatunek: Znajdź gatunek, który pojawia się najczęściej w bazie filmów, oraz podaj liczbę filmów należących do tego gatunku.
	>Gatunek z najdłuższym średnim czasem trwania: Znajdź gatunek, którego filmy trwają średnio najdłużej (runtime).
	>Histogram czasu trwania: Stwórz histogram czasu trwania filmów w gatunku o najdłuższym średnim czasie trwania.

Wymagania:
	>Python 3.7 lub wyższy Biblioteki 
	>pandas do analizy danych 
	>matplotlib do wizualizacji danych