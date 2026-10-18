FC27MOJPROJEKT MOBILE — TESTOWA PACZKA PWA

WAŻNE
- To osobna kopia testowa; nie modyfikuje aplikacji PC ani jej plików.
- Nic nie zostało wysłane na GitHub ani opublikowane.
- Dane zapisane w aplikacji PC nie synchronizują się automatycznie z telefonem.
- Dane przeglądarki są lokalne dla danej witryny/urządzenia. Regularnie eksportuj kopię JSON w ustawieniach.

ZAWARTOŚĆ
- index.html — mobilna kopia interfejsu aplikacji
- manifest.webmanifest — ustawienia instalacji PWA
- service-worker.js — podstawowy cache/offline shell
- icons/ — ikony ekranu początkowego

JAK PRZETESTOWAĆ NA KOMPUTERZE
1. Rozpakuj folder.
2. Uruchom lokalny serwer HTTP w tym folderze (np. python -m http.server 8000).
3. Otwórz http://localhost:8000 w przeglądarce.

JAK URUCHOMIĆ NA IPHONIE — DOPIERO PO PUBLIKACJI HTTPS
1. Otwórz opublikowany adres HTTPS w Safari.
2. Wybierz Udostępnij → Do ekranu początkowego.
3. Potwierdź Dodaj.

Przed publikacją należy przetestować stronę na telefonie i sprawdzić działanie importu/eksportu JSON. Ta paczka nie jest jeszcze opublikowana.
