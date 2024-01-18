**Zad 1 Docker**

3.0 obraz ubuntu z Pythonem w wersji 3.8

3.5 obraz ubuntu:22.04 z Javą w wersji 8 oraz Kotlinem

4.0 do powyższego należy dodać najnowszego Gradle’a oraz paczkę JDBC SQLite w ramach projektu na Gradle (build.gradle)

4.5 stworzyć przykład typu HelloWorld oraz uruchomienie aplikacji przez CMD oraz gradle

5.0 dodać konfigurację docker-compose


Termin: 20.10


**Zad 2 Ktor**

3.0 Należy stworzyć model Produktów z minimum czterema polami oraz metody w kontrolerze odpowiedzialne za odczyt jednego oraz wielu produktów; metody powinny zwracać JSONa; należy stworzyć odpowiednią tablicę routingu; dane powinny być zapisane w bazie danych, np. SQLite

3.5 Należy stworzyć dwa modele, np. Produkty oraz Kategorie, z jedną relacją oraz minimum czterema polami

4.0 Należy stworzyć metody CRUD po REST dla modeli z oceny 3.5

4.5 Należy aplikację uruchomić na dockerze (stworzyć obraz) oraz dodać Ngrok

5.0 Należy dodać konfigurację CORS dla dwóch hostów dla metod CRUD


Termin: 03.11

**Zad 3 Kalkulator**

3.0 Należy stworzyć prosty kalkulator z dodawaniem + opcja czyszczenia wyniku + przycisku wyniku

3.5 Należy dodać pozostałe operacje: mnożenie, dzielenie oraz odejmowanie

4.0 Należy dodać obsługę kolejnych działań na wyniku

4.5 Należy dodać procent, znak ujemny, logarytm oraz potęgę

5.0 Wersja ma się skalować na tablet (horyzontalnie, wertykalnie)


Termin: 23.11


**Zad 4 Lista zadań**

3.0 wyświetla listę z góry określonych zadań (ArrayList)

3.5 pobiera zadania via data binding

4.0 usuwanie (swipe) zadań

4.5 stworzenie view modelu z polami: nazwa, opis, data, status + widok

5.0 dodanie SQLite


Termin: 30.11


**Zad 5 Zakupy**

3.0 stworzyć listę produktów z podstroną opisu produktu (intencje), a to wszystko na fragmentach

3.5 opcja dodania produktu do koszyka

4.0 dodanie tabów między produktami, a koszykiem

4.5 dodanie więcej niż jeden produkt tego samego typu do koszyka

5.0 usuwanie produktów z koszyka (za pomocą liczby produktów)


Termin: 7.12


**Zad 6 Baza danych**

3.0 stworzenie modelów Produktów oraz Kategorii

3.5 model Koszyka

4.0 modele Produktów oraz Kategorii (z relacją)

4.5 model Użytkownika

5.0 modele w Realmie lub Firebase

Termin: 21.12


**Zad 7 Sieć**

3.0 pobieranie produktów z aplikacji serwerowej

3.5 pobieranie dodatkowo kategorii

4.0 wyświetlanie produktów oraz ich kategorii na dwóch osobnych listach

4.5 zapis danych lokalnie

5.0 dodawanie produktów z poziomu aplikacji mobilnej

Termin: 30.12


**Zad 8 Logowanie i rejestracja**

3.0 logowanie przez aplikację serwerową

3.5 rejestracja przez aplikację serwerową

4.0 logowanie via Google OAuth2

4.5 logowanie via Facebook lub Github OAuth2

5.0 zapisywanie danych logowania OAuth2 po stronie serwera

Termin: 7.01


**Zad 9 Płatności**

3.0 formularz płatności oraz mockowanie przez aplikację serwerową

3.5 model płatności lokalnie

4.0 lista zakupionych (opłaconych) produktów + model

4.5 wdrożenie stripe'a

5.0 dodanie opcji przez PayU

Termin: 25.01


**Zad 10 Testy**

3.0 stworzyć 50 testów funkcjonalnych 

3.5 stworzyć dodatkowo 20 testów jednostkowych

4.0 stworzyć mocki modeli produktów oraz kategorii

4.5 dodać fixturki

5.0 uruchomić testy na browserstack na minimum 2 urządzeniach

Termin: 1.02
