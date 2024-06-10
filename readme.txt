
Projekt: iframe Padlet Board


Dateien
- index.html: Die Hauptdatei des Projekts, welche die Struktur der HTML-Seite enthält.

Aufbau der HTML-Datei

1. HTML Kopfbereich (<head>)
    - Meta-Tags: Enthält Meta-Tags für Zeichensatz und Viewport-Einstellungen.
    - Titel: Setzt den Seitentitel auf "iframe Padlet Board".
    - PIWIK Script: Ein eingebettetes Script zur Implementierung von Piwik Pro für das Benutzertracking.
    - CSS Styles: Inline CSS zur Gestaltung der Seite, einschließlich responsiver Design-Anpassungen.

2. HTML Körper (<body>)
    - Header (<header>): Enthält die Navigationsleiste mit drei Links:
        - Veranstaltungen: Link zu einem Veranstaltungskalender.
        - FAQ: Link zu einem FAQ-Dokument auf Google Drive.
        - Filter nach Aktivitäten: Link zu einem Filterdokument auf Google Drive.
    - IFrame: Ein eingebettetes Padlet Board, das die Veranstaltungen und Aktivitäten anzeigt.

Funktionen und Features

1. Responsives Design
    - Die Seite passt sich verschiedenen Bildschirmgrößen an, von mobilen Geräten bis zu Desktop-Computern.
    - Die Navigationsleiste befindet sich bei kleineren Bildschirmen am unteren Rand des Bildschirms.

2. Navigation
    - Links zu verschiedenen Ressourcen sind in der Navigationsleiste enthalten.
    - SVG-Icons werden für die Links verwendet, um sie optisch ansprechender zu gestalten.

3. IFrame
    - Das eingebettete Padlet Board zeigt Inhalte in einem IFrame an und passt seine Höhe dynamisch an die Größe des Bildschirms an.

4. Piwik Pro Integration
    - Ein Script zur Integration von Piwik Pro für das Tracking von Benutzerinteraktionen.

Anpassungen
- Farben und Layout: Farben und Layout können durch Bearbeitung der CSS-Variablen im <style>-Tag angepasst werden.
- Links: Die Links in der Navigationsleiste können bei Bedarf geändert werden, indem die href-Attribute der <a>-Tags bearbeitet werden.
- Padlet Board: Die URL des Padlet Boards kann durch Bearbeitung des src-Attributs des <iframe>-Tags geändert werden.



Kontakt
Bei Fragen oder Problemen wenden Sie sich bitte an den Entwickler.

Laurenz.freuen@moenchengladbach.de
------


