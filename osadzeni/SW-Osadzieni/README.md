# Rejestr osadzonych SW

Moduł skopiowany z kaczorkacper28/SW-Osadzieni. Zawiera 45 fikcyjnych paragrafów RP i dostęp do komend dla stopni od Kaprala do Inspektora Generalnego SW.

## Uruchomienie

W tym folderze wykonaj `npm install`, ustaw zmienne `TOKEN`, `CLIENT_ID`, `GUILD_ID` (lub lokalny plik `.env`), następnie `npm start`. Na hostingu ustaw katalog roboczy na `osadzeni/SW-Osadzieni`.

To samodzielny bot. Używa własnego klienta Discord. Nie uruchamiaj drugiej kopii tego samego bota równocześnie. Rejestracja komend zastępuje komendy tej aplikacji na wskazanym serwerze; użyj jej dotychczasowych danych aplikacji SW-Osadzieni.

Przy przenoszeniu istniejącej usługi zachowaj folder `data/` z rejestrem osadzonych. Dane i sekrety nie są przechowywane w Git.

## Paragrafy RP

W `/osadzony-dodaj` i `/osadzony-edytuj` pole `paragraf` podpowiada pozycje po numerze (np. `45`, `§3`) lub nazwie (np. `kradziez`). Wyświetla do 25 wyników jednocześnie; wszystkie 45 pozycji są dostępne przez wyszukiwanie. Można też wpisać kilka paragrafów ręcznie.

Minuty przy podpowiedziach są sugerowanymi wyrokami RP. Wyrok i godziny wpisuje się osobno, a licznik wynika z godzin początku i końca. Taryfikator nie jest rzeczywistym Kodeksem karnym.

Zmiany pojawią się po wdrożeniu i restarcie bota, który ponownie zarejestruje komendy.
