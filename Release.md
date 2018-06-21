<p align="center">
  <img src="https://github.com/ZeusLukaz/SA-MP-Life-of-Crime/blob/Release/Logo.png" alt="LoC Logo"/>
</p>

## Feature Tabelle

- [Behobene Fehler](#behobene-fehler)
- [Neu hinzugefügt](#neu-hinzugefügt)

## Behobene Fehler

- Fraktionshäuser wurden nach dem setzen nicht in der Datenbank gespeichert.
- Schwerwiegender Dialog Bug behoben mit welchen man Unendlich Geld Buggen konnte.
- Falls der Spieler im Knast oder Prison war und gefreezt war wird er beim entlassen entfreezt.
- Spieler werden nun im Knast oder Prison 5 Minuten gefreezt wenn sie Angreifen.
- Gegenstände werden abgenommen beim /arrest oder tot ausgelöst von einen Beamten mit Wanteds (Samen, Grass, Meth, Kokain, Goldbaren, Materialien und Waffen)
- Service Haushuren Fehler bei keiner Immobiele und es konnte nur Hure 1 Bestellt werden
- Trucker Ladungen können in einen umkreis von 7.5 Metern anstat 5 Metern gekauft werden
- Trucker Skill stieg bei jeder abgabe z.B. 1 Liter = 1 Exp
- Sanitäter Nachrichten wurden beim Tod dem Sterbenden angezeigt
- Übersichtlicherer Text Holzfäller
- Gangfight Anzeige Verschwindet nicht für Verteidiger wenn die Angreifer gewinnen
- Holzfäller Fahrzeuge spawnen zu schnell alle davor 5 min danach 10 min
- Job Fortschrittanzeige Position angepasst
- Job Fortschrittanzeige Müllmann erweitert
- TextDraw Umlaute Encodierer eingefügt
- AntiSpawnKill über den Spieler zu hoch
- Müllmann TextDraw wurde bei /accept angezeigt ohnte einer Tour
- Müllmann TextDraw updatet nicht bei Spieler 1 wenn Spieler 2 abgiebt
- AntiSpawnKill anzeige bleibt falls ein Spieler mit ihr stirbt
- ATM Flint County entfernen oder verschieben wegen 24/7 Eingang (entfernt)
- Alle ActionProxy Nachrichten buggen
- PayDay Anzeige ist nicht vollständig (Festgeld Dauer wurde immer per Timestamp gesetzt)
- Pizza Interiors gingen nicht
- /makeleader geht über die Datenbankeinträge
- /confiscate Meth kann nicht konfisziert werden
- /confiscate Plantage und Kokaintasche wurde nicht angezeigt wenn man nicht an der Position ist
- /motorradschein /waffenschein und /truckschein gefixt
- Tutorial kann nicht gemacht werden wenn man bereits einen Personalausweiß hat
- Zivilisten konnten alle Häuser betreten
- Plantagen TextLabel wurde überall angezeigt (Alle TextLabel Variablen die Dynamisch genutzt werden wurden nicht zurückgesetzt)
- Tankstellen 3DTextLabel Anzeige wurde beim Updaten nicht komplett angezeigt
- /scheine Mautpass wurde als Autoschein angezeigt
- Alle ZeitRechnungs Funktionen wurden angepasst
- Detektiv Sperrzeit Fehler (Gesamter ZeitRechnungs Fehler)
- Alle Berufe hatten einen zufrühen return beim Max Skilllevel
- Bei einen Bankalarm wurde in der HQ Nachricht das HQ mehrmals angezeigt (Anzahl der Enums)
- Animationen werden beim Spawn Geladen um den Sync zu verbessern
- Toten Icon wurde nicht entfernt wenn der Spieler per /unjail befreit wurde
- Spieler wurden ins Gefängniss gesteckt wenn er von einen Cop getötet wurde welcher nicht im Polizeidienst ist
- Hochseefischer /fischer info anzeige wurde die Reusen ID im String vor dem String gesetzt
- /grab wurde gefixt
- AntiSpawnkill geht nicht weg
- /help /frakhelp fehlt
- Roadblock ID wurde mit der Fraktions ID verwechselt
- Godmode wird beim verlassen des Servers entfernt
- Das Swat Abseilen wird nur abgefragt wenn man in einem PD Helikopter ist
- TimestampToDate lies den Server crashen

## Neu hinzugefügt

- Cops und Admins können Waffen abnehmen können
- Busfahrer, Pilot, Holzfäller, Zugfaherer und Hochseefischer Fortschrittanzeige
- AntiSpawnKill eingefügt
- Logs erstellt
- No-DM Zonen eingefügt mit Log (Stadthalle, Airport LS, Airport SF, Airport LV)
- Registrierung, Premium und Adminlevel in den Statistiken einsehbar
- /search eingefügt für Cops und Ordnungsamt (Fahrzeug durchsuchen)
- /confiscate Cops können Kokaintaschen, Plantagen, Meth und Fahrzeug Gegenstände konfiszieren
- /destroyweed Admins können Plantagen zerstören
- /godmode Admins können Godmode vergeben
- /vehinfo Cops & Ordnungsamt können Fahrzeug Informationen abrufen
- /abdonetutorial Tutorial abbrechen
- /unjail Spieler von Knast und Prison befreien
- /respawnfrakcars Leader können Fraktionsfahrzeuge einmal in der Stunde neu spawnen
- /dropweapons Falls man eine Waffe besitzt
- /disarm Spieler entwaffen
- /memberliste wie /adminliste
- Mechaniker System Fahrzeuge an Position Liefern lassen
- LoC Bank Mapping by Oskar
- Cops können sich abseilen können (nur im SWAT Modus)
- Admins können Admindienst Skins auswählen
- Häuser in der Datenbank mit ImmobielenID verbessert
- Haus Tänzer eingefügt
