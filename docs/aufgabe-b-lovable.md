# Aufgabe B – Entwicklung mit Lovable

## Ziel

Eine funktionsfähigen Webanwendung das so ausschaut wie das vorher entwickelte UI-Design von Google Stitch.

## Projekt

AlfPASS

## Verwendetes Tool

Lovable

## Ziel

Von Google Stitch entworfenes Design soll als funktionierende Webanwendung umgesetzt werden mit frontend und Backend 

## Verwendete Prompts

Prompt 1

Erstelle eine Webanwendung für einen Passwortmanager mit dem Namen „AlfPASS“.
Die Anwendung soll auf dem beigefügten entworfenen Design aufbauen und komplett funktionsfähig sein.
Diese Seiten sollen enthalten sein:
- Login
- Registrierung
- Dashboard
- Passwort-Tresor
- Passwort hinzufügen
- Passwort bearbeiten
- Passwortgenerator
- Einstellungen
Diese Funktionen sollen umgesetzt werden:
- Benutzer können sich registrieren und anmelden.
- Passwörter können angelegt, bearbeitet und gelöscht werden.
- Passwörter können nach Kategorien sortiert werden (Arbeit, Privat, Banking, Social Media).
- Ein Passwortgenerator erstellt sichere Passwörter.
- Die Passwortstärke wird angezeigt (in rot mit dem wort schwach wenn schwach in gelb mit dem Wort Mittel und in grün mit dem wort stark) 
- Passwörter können mit einem Klick kopiert werden.
- Unterstützung für Hell- und Dunkelmodus.
- Zwei-Faktor-Authentifizierung als vorbereitete Funktion.
- Verwaltung vertrauenswürdiger Geräte (Geräte hinzufügen und entfernen).
- Dashboard mit Sicherheitsübersicht und Statistiken.
Es soll modern aussehen und dem angehängten UI-Design entsprechen.
Verwende React und TypeScript.
Erzeuge zunächst eine lauffähige Version mit Frontend und einer einfachen Backend-Logik beziehungsweise Mock-Daten.
Der Code soll übersichtlich aufgebaut sein und später leicht in Frontend, Backend und ein separates Verschlüsselungsmodul aufgeteilt werden können.


Prompt 2

Biometrie soll mit apple Face id und bei android mit finger abruck und face id möglich sein

Erweitere außerdem die Seite Einstellungen und mache sie zu einer vollständigen Einstellungsseite für einen modernen Passwortmanager.

Füge zum Beispiel folgende Bereiche hinzu:

Sicherheit

Anmeldung mit Biometrie ermöglichen.

Auf Apple-Geräten soll Face ID oder Touch ID verwendet werden.

Auf Android-Geräten soll Fingerabdruck oder Gesichtserkennung verwendet werden.

Zwei-Faktor-Authentifizierung (Authenticator-App oder Sicherheitsschlüssel).

Master-Passwort ändern.

Automatische Sperre nach 1, 5, 10 oder 30 Minuten Inaktivität.

Wiederherstellungsschlüssel anzeigen und neu generieren.

Vertrauenswürdige Geräte

Liste aller angemeldeten Geräte.

Gerät umbenennen.

Gerät entfernen.

Letzte Anmeldung mit Datum, Uhrzeit und Standort anzeigen.

Datenschutz

Zwischen lokalem Speicher und Cloud-Synchronisation wählen.

Export des Passwort-Tresors als verschlüsselte Datei.

Import einer Sicherungsdatei.

Benachrichtigungen

Benachrichtigung bei Anmeldung auf neuem Gerät.

Warnung bei unsicheren oder mehrfach verwendeten Passwörtern.

Hinweis bei möglichem Datenleck.

Darstellung

Hell-/Dunkelmodus.

Sprache (Deutsch/Englisch).

Schriftgröße.

Füge unter den Einstellungen zusammen was am besten unter einem Punkt zusammen gehört zum Beispiel sicherheit und mach dann dort die weiteren Unterpunkte

--- Es wurde leider nichts geändert. Die Seite Einstellungen ist weiterhin leer obwohl ich in dem Prompt geschrieben habe er soll das ergänzen und meine Lovable credits sind ausgeschöpft

Prompt 3 

Die Seite /einstellungen wurde nicht mehr gerendert und bleibt leer. Es scheint einen Laufzeitfehler oder React-Fehler zu geben. Bitte behebe den Fehler und stelle sicher, dass alle Einstellungen korrekt angezeigt werden. Die bestehende Funktionalität soll erhalten bleiben.

Außerdem füge noch eine Seite hinzu mit einem Sicherheitscenter

Darin könnte zum Beispiel stehen:

Sicherheitsbewertung des Tresors (0–100)

Anzahl schwacher Passwörter

Doppelte Passwörter

Kompromittierte Passwörter

Empfehlung zur Verbesserung


Fixingbenachrichtigung von Lovable: 

Beide Fixes sind live: Die Einstellungsseite bleibt nicht mehr leer (Ursache war ein fehlender Profildatensatz — getProfile() legt jetzt bei bestehender Session automatisch das Standardprofil an), und das neue Sicherheitscenter unter /sicherheit zeigt Score (0–100), schwache/doppelte/kompromittierte Passwörter und Empfehlungen.

## Ergebnis


Der erste Teil hat gut funktioniert. Ich habe aber von Anfang an die Einstellungen nicht weiter definiert deshalb war die Seite leer. Beim versuch das zu ändern und es noch mit leben zu befüllen. Das hat leider nicht ganz funktioniert und trotz meines Prompts war die Seite weiterhin leer. 
Beim Versuch das zu ändern waren die Credits aufgebraucht 