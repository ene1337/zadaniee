1. Analiza wymagan – Magazyn Elektro-Bud
2. Wymagania funkcjonalne

FR.01. Logowanie – pracownik loguje sie za pomoca loginu i hasla lub karty RFID. Kazdy ma swoje konto

FR.02. Wyszukiwanie towaru – mozna znalezc towar po kodzie EAN lub nazwie

FR.03. Lokalizacja towaru – system pokazuje gdzie znajduje sie dany towar np. S1R2P3

FR.04. Przyjecie towaru – magazynier dodaje towar do magazynu i zapisuje jego ilosc date oraz osobe ktora go przyjela

FR.05. Wydanie towaru – po wydaniu towaru jego ilosc na magazynie zostaje zmniejszona

FR.06. Blokada braku towaru – system nie pozwala wydac wiecej towaru niz jest na stanie

FR.07. Edycja produktow – kierownik moze dodawac nowe produkty i zmieniac ich dane

FR.08. Historia operacji – kierownik moze sprawdzic kto i kiedy przyjal lub wydal towar

FR.09. Raporty – system pozwala tworzyc raporty o stanie magazynu

FR.10. Konta uzytkownikow – administrator dodaje konta zmienia uprawnienia i resetuje hasla

FR.11. Jednoczesne operacje – system zabezpiecza sie przed bledami gdy dwoch magazynierow wydaje ten sam towar w tym samym czasie

3. Wymagania niefunkcjonalne

NFR.01. Szybkosc – wyszukiwanie i skanowanie towaru powinno trwac nie dluzej niz 1-2 sekundy

NFR.02. Bezpieczenstwo – kazdy pracownik ma swoje konto a hasla sa odpowiednio zabezpieczone

NFR.03. Uprawnienia – kazdy ma dostep tylko do funkcji potrzebnych mu do pracy

NFR.04. Dostep zdalny – kierownik moze sprawdzac raporty rowniez poza magazynem

NFR.05. Interfejs – wyglad systemu jest prosty i czytelny zeby mozna bylo szybko wykonywac operacje

4. Aktorzy systemu

Magazynier – szuka towarow sprawdza gdzie leza oraz przyjmuje i wydaje produkty

Kierownik – dodaje i zmienia produkty sprawdza historie operacji i tworzy raporty

Administrator – zaklada konta pracownikom ustawia uprawnienia i resetuje hasla

5. Diagram przypadkow uzycia

Magazynier – logowanie wyszukiwanie towaru sprawdzanie lokalizacji przyjmowanie i wydawanie towaru

Kierownik – logowanie wyszukiwanie towaru edycja produktow sprawdzanie historii i raportow

Administrator – logowanie i zarzadzanie kontami

Przy przyjeciu i wydaniu towaru system sprawdza dane oraz aktualny stan magazynu

Przy wydawaniu towaru system sprawdza czy jest go wystarczajaco duzo

6. Relacje include i extend

Include – przy wydaniu towaru system zawsze sprawdza czy odpowiednia ilosc jest dostepna na magazynie

Extend – blokada wydania uruchamia sie wtedy gdy magazynier chce wydac wiecej towaru niz jest na stanie

System dodatkowo zabezpiecza stan magazynu przed bledami gdy kilka osob jednoczesnie wydaje ten sam towar