# Projekt z aplikacji mobilnych
Zespoły projektowe powinny składać się z trzech członków (A, B i C), z jasno wytyczoną odpowiedzialnością za elementy projektu.

### Odpowiedzialność członków zespołu
- **A** — *lider projektu* Opracowanie modelu danych, dokumentacja interfejsu programistycznego oraz prototypowanie interfejsów użytkownika.
- **B** — Implementacja serwerowej części systemu i opracowanie jej testów jednostkowych.
- **C** — Implementacja i dokumentacja mobilnej części systemu .

### Kroki milowe projektu
1. Deklaracja tematyki projektu (strona A4 opisu) i przedłożenie modelu danych (w formie schematu relacyjnej bazy danych).
2. Przedłożenie dokumentacji interfejsu programistycznego (przykładowo w narzędziu [Apiary](https://apiary.io)).
3. Udostępnienie i prezentacja (w postaci testów jednostkowych) implementacji serwerowej części systemu.
4. Przedłożenie prototypów (przykładowo w formie Wireframes) widoków aplikacji.
5. Prezentacja finalnego systemu.

### Kształt projektu
Projekt składa się z trzech części:
1. Aplikacji serwerowej, pozbawionej graficznego interfejsu użytkownika, skomunikowanej z bazą danych i udostępniającą interfejs programistyczny (API), zrealizowany w architekturze REST, uzupełniony o testy jednostkowe, weryfikujące poprawność implementacji. *Na wykładzie i laboratoriach przedstawione zostanie to na przykładzie frameworku Ruby on Rails.*
2. Aplikacji mobilnej, skomunikowanej z aplikacją serwerową za pośrednictwem interfejsu programistycznego. *Na wykładzie i laboratoriach przedstawione zostanie to na przykładzie Android SDK.*
3. Dokumentacji projektowej, na którą składa się:
	- krótki opis projektu,
	- schemat modelu bazy danych,
	- dokumentacja interfejsu programistycznego (lista wszystkich zasobów, ścieżek dostępu, stosowanych parametrów i reprezentacji danych),
	- prototypy widoków,
	- dokumentacji aplikacji mobilnej (wygenerowany z kodu źródłowego opis wszystkich zaimplementowanych klas).

### Dodatkowe elementy oceniania
- poprawność autentykacji użytkowników
- poprawność projektu interfejsu programistycznego w architekturze REST
- estetyka interfejsu,
- responsywność interfejsu użytkownika (przystosowanie do różnych rozdzielczości i orientacji ekranu urządzenia),
- **bespośrednia komunikacja pomiędzy aplikacją mobilną a znajdującą się na serwerze bazą danych skutkuje natychmiastową i bezwzględną oceną niedostateczną**
