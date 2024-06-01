Gra w wisielca

Funkcjonalność aplikacji i menu interfejsu konsolowego
Po uruchomieniu aplikacja proponuje rozpoczęcie nowej gry lub wyjście z aplikacji
Podczas rozpoczęcia nowej gry losowo wybierane jest słowo, a gracz rozpoczyna proces jego odgadywania
Po wprowadzeniu każdej litery wyświetlamy w konsoli licznik błędów, aktualny stan wisielca
Po zakończeniu gry wyświetlamy wynik (zwycięstwo lub porażkę) i wracamy do stanu #1 - propozycji rozpoczęcia nowej gry lub wyjścia z aplikacji

"Random Word Selector" - klasa do losowego wybierania słów.
"Word Mask Operator" - klasa odpowiedzialna za tworzenie maski słowa i zarządzanie nią. Stopniowo odkrywa maskę, jeśli użytkownik zgaduje literę.
"Hangman Drawer" - klasa odpowiadająca za rysowanie wisielca w konsoli w zależności od liczby popełnionych błędów.
"Game" - klasa zawierająca logikę użytkownika menu i działania gry.
"Game Starter" - punkt wejścia do programu, zawierający metodę main.
