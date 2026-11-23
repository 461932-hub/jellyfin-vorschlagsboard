Aktuelle Version ist **Vorschlagsboard 2.0.0.5 für Jellyfin 12.4**.

Alle normalen Nutzer sehen bei den Vorschlägen **Anonym**. Nur Administratoren
sehen die gespeicherten Namen. Das gilt für vorhandene und neue Vorschläge
und wird im Server bei jeder API-Antwort geprüft.

Zum Aktualisieren im Jellyfin-Plugin-Katalog Version 2.0.0.5 installieren,
Jellyfin neu starten und die Webseite beziehungsweise Handy-App neu öffnen.

# jellyfin-vorschlagsboard

## Vorschlagsboard 2.0.0.4

Vorschlaege erstellen und abstimmen, eingebettet in Jellyfin 12.4.
Auf dem Handy steht das Board im Seitenmenue unter den Bibliotheken.
Die Desktop-Navigation behaelt den Eintrag am Ende der Bibliotheksleiste.

**Installation/Update:** Im Jellyfin-Plugin-Katalog Vorschlagsboard 2.0.0.4
waehlen, installieren, Jellyfin neu starten und die Handy-App neu oeffnen.
Danach: Menue oben links -> Vorschlagsboard.

Repository-URL:
`https://raw.githubusercontent.com/461932-hub/jellyfin-vorschlagsboard/main/manifest.json`

Das Update gilt fuer die webbasierte Oberflaeche, wie sie die offizielle
Android-Handy-App verwendet. Andere native Clients sind nicht getestet.
33 Browserfaelle mit dem gebauten Plugin auf einer isolierten Jellyfin-12.4-
Instanz bestanden, einschliesslich Originaloberflaeche und Cinema Preview27.
Kein physischer Handy-App-Test. Vorhandene Daten und Sicherheitspruefungen
bleiben erhalten; der Medienzugriffsschutz-Eintrag im Katalog bleibt unveraendert.

Quellcode, Pruefberichte und Installationshinweise liegen neben dem ZIP-Paket.
