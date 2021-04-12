# Travelboard :earth_americas::v:
## Dokumentacja: 

### 1. Charakterystyka  oprogramowania 
Nazwa skrócona: TravelBoard

Nazwa pełna: TravelBoard - asystent podróżnika

Krótki opis ze wskazaniem celów: Aplikacja mobilna służąca jako asystent podróży, która pomoże użytkownikowi w wyborze atrakcji w podróży, pokazująca prognozę pogody w określonym miejscu i pozwalająca po przejrzeniu informacji prowadzić osobisty dziennik wpisów.

### 2. Prawa autorskie 
Autorzy: Eliza Sinkevich, Hanna Zhuk, Irina Frolova

Licencja: MIT

### 3. Specyfikacja wymagań

#### Wymagania funkcjonalne
| Identyfikator | Kategoria | Podkategoria | Nazwa krótka | Opis | Priorytet |
|:-:|:-:|:-:|:-:|:-:|:-:|
|1|funkcjonalne||Wybór miasta|Możliwość ustawienia swojego miasta|1|
|2|funkcjonalne||Mapa z atrakcjami|Wyświetlenie mapę regionu wraz z orientacyjną lokalizacją atrakcji w postaci pinezek na mapie|1|
|3|funkcjonalne||Informacja o atrakcji|Po kliknięciu na pinezkę system powinien wyświetlić podstawowe informacje o atrakcji: nazwę, opis, lokalizację|1|
|4|funkcjonalne||Wyszukiwarka atrakcji|Wyszukiwanie atrakcji w sposób przeklikania zdjęć z opisem|2|
|5|funkcjonalne||Filtrowanie atrakcji|Możliwość filtrowania atrakcji według zainteresowań|3|
|6|funkcjonalne||Pogoda|Wyświetlenie informacje meteorologiczne w zakładce "Pogoda"|3|
|7|funkcjonalne||Podłączenie bazy danych|Zapis danych z wykorzystaniem SQLite|2|

#### Wymagania niefunkcjonalne
| Identyfikator | Kategoria | Podkategoria | Nazwa krótka | Opis | Priorytet |
|:-:|:-:|:-:|:-:|:-:|:-:|
|1|niefunkcjonalne|Statystyki||Dokładny zapis statystyk|2|
|2|niefunkcjonalne|Nawigacja||Szybka nawigacja w aplikacji |1|
|3|niefunkcjonalne|Bezpieczeństwo||Zgodność z wymogami bezpieczeństwa|2|
|4|niefunkcjonalne|Elastyczność integracji||Elastyczność pod względem możliwości integracji z innymi popularnymi serwisami społecznościowymi |3|
|5|niefunkcjonalne|Dostępność|| Dostęp dla użytkowników do użytku w dowolnym momencie |1|
|6|niefunkcjonalne|Prywatność||Zachowanie prywatności użytkowników|2|


### 4. Projekt (język UML)

### 5. Architektura systemu/oprogramowania

#### Architektura rozwoju 
| Lp | Nazwa produktu | Przeznaczenie w projekcie | Wersja  | 
|:-:|:-:|:-:|:-:|
|1|Java|||
|2|SQLite| | 3.35.3 |
|3|DBFlow||4.2.4|


#### Architektura uruchomieniowa 
| Lp | Nazwa produktu | Przeznaczenie w projekcie | Wersja  | 
|:-:|:-:|:-:|:-:|
|1|Android Studio|Środowisko IDE używane przy tworzeniu projektu||
|2|Windows 10 |System operacyjny używany przy tworzeniu projektu||
|3|Git| Systemy kontroli wersji aplikacji |2.31.1|
|4|GitHub| ||


### 6. Testy

