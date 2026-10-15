1. analiza wymagan – magazyn elektro-bud
2. wymagania funkcjonalne

fr.01. logowanie – login i haslo lub karta rfid, kazdy pracownik ma swoje konto.

fr.02. wyszukiwanie towaru – szukanie po kodzie ean lub nazwie.

fr.03. lokalizacja towaru – system pokazuje, gdzie lezy towar, np. s1r2p3.

fr.04. przyjecie towaru – dodawanie towaru do magazynu z zapisem ilosci, daty i osoby.

fr.05. wydanie towaru – zmniejszanie stanu po wydaniu towaru.

fr.06. blokada braku towaru – nie mozna wydac wiecej, niz jest na stanie.

fr.07. edycja produktow – kierownik dodaje i zmienia produkty.

fr.08. historia operacji – kierownik sprawdza, kto i kiedy przyjal lub wydal towar.

fr.09. raporty – tworzenie raportow o stanie magazynu.

fr.10. konta uzytkownikow – admin dodaje konta, zmienia uprawnienia i resetuje hasla.

fr.11. jednoczesne operacje – system zapobiega bledom, gdy dwie osoby wydaja ten sam towar.

3. wymagania niefunkcjonalne

nfr.01. szybkosc - system reaguje w 1-2 sekundy.

nfr.02. bezpieczenstwo – hasla sa zabezpieczone, a kazdy ma swoje konto.

nfr.03. uprawnienia – kazdy ma dostep tylko do swoich funkcji.

nfr.04. dostep zdalny – kierownik moze sprawdzac raporty poza magazynem.

nfr.05. interfejs – prosty wyglad, wygodny do szybkiej pracy.

4. aktorzy systemu

magazynier – szuka towaru oraz przyjmuje i wydaje produkty.

kierownik – zarzadza produktami, sprawdza historie i raporty.

administrator – tworzy konta i ustawia uprawnienia.

5. diagram przypadkow uzycia

magazynier: logowanie, szukanie towaru, sprawdzanie lokalizacji, przyjecie i wydanie.

kierownik: logowanie, szukanie towaru, edycja produktow, historia i raporty.

administrator: logowanie i zarzadzanie kontami.

przyjecie i wydanie towaru lacza sie ze sprawdzeniem dostepnosci.

blokada ujemnego stanu uruchamia sie przy probie wydania zbyt duzej ilosci towaru.

6. relacje include i extend

include – sprawdzenie dostepnosci jest wymagane przy operacjach magazynowych.

extend – blokada ujemnego stanu uruchamia sie, gdy ktos probuje wydac wiecej towaru, niz jest na magazynie, lub gdy wystepuje problem przy jednoczesnym wydawaniu.
