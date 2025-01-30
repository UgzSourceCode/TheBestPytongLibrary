## Wyznaczanie granic spójności
 Znaleziono konteksty:
  - Zarządzanie przedmiotami - zarządzanie książkami z opcją łatwego rozszerzenia np na kasety i płyty które czasem też są wypożyczane w bibliotekach
	  - Heurystyki:
		  - Intuicja :D - tak mi mówi moje doświadczenie zawodowe
		  - Czy odpowiada na jedno pytanie? tak odpowiada na pitanie o stan książki(posiadanie, dostępność itd)
  - Wypożyczenia - moduł odpowiedzialny za wypożyczanie książek
	  - Heurystyki:
		  - Intuicja: bo tak
		  - Czy odpowiada na jedno pytanie? tak kto ma książke teraz lub miał ją w przeszłości
  - Użytkownicy
	  - Heurystyki:
		  - Intuicja
  - Kary - system płatności i zarządzania należnościami
	  - Heurystyki:
		  - Intuicja
  - Whishlista - zarządzania przedmiotami których chcą użytkownicy
	  - Heurystyki:
		  - Intuicja
		  - 

Zauważyliśmy że dość łatwo było podzielić system na granice spójności patrząc na źródła prawdy które nam się ujawniły na poprzednich etapach. I nie widzimy potrzeby mocniejszego rozdrabniania systemu.

System można było rozproszyć trochę mocniej, ale skomplikowało by to implementację na poziomie MVP. Bez pewności korzyści biznesowych, a w przyszłości jeśli np będzie potrzeba zoptymalizowania fragmentu jakiegoś modułu to będzie można to zrobić jeszcze w prosty sposób.

## Weryfikacja
