# BackendZadanieRekrutacyjne


##  Zadanie Django Rest

Właściciel stacji benzynowej pilnie poszukuje osoby potrafiącej stworzyć bazę danych niezbędną do sprawnego przyjmowania zamówień. W bazie tej mają się znaleźć informacje o kupujących, klasa benzyny ( 95oktanów , 98oktanów ), typach benzyny ( diesel, benzyna, gaz ), zakupionym typie oraz rodaju benzyny:
Pamiętaj, że
* każde kupno benzyny wiąże się z kupnem jednego rodzaju typu i klasy benzyny,
* kupujący może kupować wiele typów benzynę o różnych klasach,
* właściciel powinien mieć dostęp do historii zakupów klienta wraz z ich datą

Dane użytkownika:
- imie, nazwisko ( varchar 50 )
- zdjecie ( file )

Przygotuj diagram ERD

2. Zaimplementuj diagram bazy danych do Django Rest wykorzystując ORM.
3. Zaimplementuj metody list, retrieve, update, delete.
4. Tylko właściciel ( admin ) może aktualizować dane oraz je dodawać i odczytywać całość
5. Uzytkownik ma prawo odczytu tylko swoich danych
6. Zaimplementuj metodę zapisywania zdjęć do dowolnego zewnętrznego dostawcy np. cloudinary
7. Zainstaluj /swagger lub openapi by generowało się automatycznie z API
8. Uruchom API na zewnętrznym linku

## Zadanie opcjonalne ( Zaimplementuj testy dla API poszczególnych endpointów oraz modeli )



