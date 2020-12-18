# TabelServer
Server med henblik på at sende tabel data i txt fil-format



Dette programs funktioner er at sende tabel data fra en tekst fil fra én computer til en anden
ved at sætte en serversocket op der kan modtage en socket fra en klient med den rigtige IP eller med lokalhost
klient socketet benytter tostring metode til at lave en outputstream som serveren kan opfange

Server socketet acceptere klient socketet og får inputstreamen som dernæst skrives ind i et 
txt dokument på en tilladt plads i systemet med navnet "roger.txt" (OBS, Denne fils plads skal angives i koden ved FileOutputStream)

Dataen bliver sendt med TCP-protokol i mindre pakker og korregeres med three-way-handshake.

Programmet er skrevet og opgives med en dummy tabel navngivet "temp.txt". Programmet er sadt op således 
at text dokumentet kan aflæses korrekt og med linje nummerering og mellemrum som forventet



