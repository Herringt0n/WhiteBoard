#####  WHITE BOARD  #####
Aplikacja do rysowania

###  OPIS  ###
White Board to prosta aplikacja desktopowa napisana w Pythonie, z wykorzystaniem biblioteki Tkinter. Umożliwia rysowanie na wirtualnej tablicy, wybór koloru pędzla, zmianę grubości linii oraz wstawianie obrazów graficznych.

###  LOGO  ###
Logo aplikacji znajduje się w pliku logo.png i jest ustawione jako ikona okna aplikacji.

###  PRZEZNACZENIE  ###
Aplikacja realizowana na potrzeby zaliczenia projektu.

###  WYMAGANIA FUNKCJONALNE  ###
- rysowanie na obszarze roboczym przy użyciu myszy
- wybór koloru z palety
- zmiana grubości lini za pomocą suwaka
- czyszczenie całego obszaru rysowania
- wstawianie obrazów w formacie PNG na obszar roboczy
- prosty i intuicyjny interfejs użytkownika

###  WYMAGANIA NIEFUNKCJONALNE  ###
Technologia:
- aplikacja napisana w języku Python
- wykorzystanie biblioteki Tkinter
- uruchamiana jako aplikacja desktopowa

Wydajność:
- aplikacja powinna reagować na ruch myszy w czasie rzeczywistym
- rysowanie linii nie powinno powodować zauważalnych opóźnień

Bezpieczeństwo:
- aplikacja działa lokalnie
- nie przechowuje danych użytkownika
- nie wymaga połączenia z internetem

Równoległość:
- jednowątkowa aplikacja
- obsługa zdarzeń realizowana jest przez pętlę zdarzeń Tkintera

###  MODUŁY SYSTEMU  ###
Moduł rysowania - obsługa rysowania linii na canvasie
Moduł palety kolorów – wybór aktualnego koloru pędzla
Moduł kontroli grubości linii – suwak zmieniający szerokość linii
Moduł zarządzania canvasem – czyszczenie obszaru roboczego
Moduł obsługi obrazów – wstawianie plików graficznych

###  PRZYPADKI UŻYCIA  ###
1. Rysowanie:
     - Użytkownik naciska lewy przycisk myszy
     - Przesuwa kursor po canvasie
     - Aplikacja rysuje linię zgodnie z ruchem myszy
2. Zmiana koloru:
     - Użytkownik klika wybrany kolor z palety
     - Nowe linie są rysowane w wybranym kolorze
3. Zmiana grubości linii:
     - Użytkownik przesuwa suwak
     - Grubość kolejnych linii ulega zmianie
4. Wstawienie obrazu:
     - Użytkownik wybiera opcję dodania obrazu
     - Wskazuje plik PNG
     - Obraz pojawia się na canvasie

###  ARCHITEKTURA SYSTEMU  ###
Architektura aplikacji ma charakter monolityczny i cała logika aplikacji znajduje się w jednym pliku Pythona.
Elementy:
- GUI (Tkinter)
- Canvas (obszar rysowania)
- Obsługa zdarzeń myszy i suwaka

###  STOS TECHNOLOGICZNY  ###
Język - Python 3.12
GUI - Tkinter
System operacyjny - Windows / Linux / macOS

###  PROCES URUCHOMIENIA PROJEKTU  ###
1. Zainstalować Python 3
2. Pobrać repozytorium projektu
3. Upewnić się, że w katalogu znajdują się pliki:
  - main.py
  - logo.png
  - eraser.png
  - addimage.png
  - colorsection.png

4. Uruchomić polecenie:
  - python main.py

###  STRUKTURA FOLDERÓW  ###
WHITE_BOARD/
│
├── main.py
├── logo.png
├── eraser.png
├── addimage.png
├── colorsection.png
└── README.md

###  AUTORZY  ###
Jessica Welniak
Patryk Rus
