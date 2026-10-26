# Spezifikation des Terminplaners — Gliederung und Beispiele

Mitgearbeitet haben (GitHub-Benutzernamen, auch bei Einzelarbeit): @ErikCibis

🧩 1. Was das Entwicklerteam wissen muss
Ziel des Systems: Terminbuchung zwischen Studierenden und Professoren

Benutzerrollen: Studierende, Professoren, Admin

Daten, die gespeichert werden müssen

Professoren (Name, Kürzel, Räume, verfügbare Zeiten)

Studierende (Name, Matrikelnummer, Studiengang)

Termine (Datum, Uhrzeit, Raum, Professor, Student)

Ablauf der Terminbuchung

Auswahl Professor → Auswahl Zeit → Eingabe Studentendaten → Bestätigung

Regeln / Constraints

Ein Slot kann nur einmal gebucht werden

Matrikelnummer muss eindeutig sein

Professoren werden ausschließlich über Kürzel angezeigt

Ausgabe / Bestätigung

Terminbestätigung enthält Professor, Raum, Zeit, Studentendaten

Systemgrenzen

Keine automatische Raumverwaltung

Keine Synchronisation mit externen Kalendern

Fehlerfälle

Slot bereits belegt

Ungültige Matrikelnummer

Pflichtfelder fehlen

📑 2. Gliederung der Spezifikation (mit Begründung)
1. Einleitung / Zielsetzung
Begründung: Entwickler müssen zuerst verstehen, was gebaut wird und warum.

2. Benutzerrollen
Begründung: Unterschiedliche Rollen → unterschiedliche Funktionen.

3. Funktionale Anforderungen
Begründung: Kern des Systems — beschreibt, was das System tun muss.

4. Datenmodell
Begründung: Entwickler brauchen klare Datenstrukturen, um die Software korrekt aufzubauen.

5. Abläufe / Use Cases
Begründung: Zeigt, wie Nutzer mit dem System interagieren.

6. Validierungsregeln / Constraints
Begründung: Verhindert Fehler und falsche Eingaben.

7. Ausgaben / Bestätigungen
Begründung: Entwickler müssen wissen, was am Ende angezeigt wird.

8. Fehlerfälle
Begründung: Systeme müssen robust sein — Fehler müssen definiert sein.

9. Nicht-funktionale Anforderungen
Begründung: Performance, Sicherheit, UI‑Anforderungen etc.

📝 3. Beispiele je Abschnitt (kurz, wie gefordert)
1. Einleitung / Zielsetzung
Der Terminplaner ermöglicht Studierenden die Buchung von Gesprächsterminen bei Professoren über ein webbasiertes Interface.

2. Benutzerrollen
Studierende: können Termine buchen

Professoren: verwalten verfügbare Zeitfenster

Admin: legt Professoren und Räume an

3. Funktionale Anforderungen
Studierende müssen einen Termin bei einem Professor anhand dessen Kürzel auswählen können.

4. Datenmodell
Entität	Attribute
Professor	Kürzel, Name, Raum, verfügbare Slots


5. Ablauf / Use Case
Ein Student wählt Prof. „AB“, sieht freie Slots, gibt Matrikelnummer + Namen ein und erhält eine Bestätigung.

6. Validierungsregeln
Matrikelnummer muss aus genau 7 Ziffern bestehen.

7. Ausgaben / Bestätigungen
Die Bestätigung zeigt: Professor (Name + Kürzel), Raum, Datum, Uhrzeit, Studentendaten.

8. Fehlerfälle
Wenn ein Slot bereits belegt ist, wird die Meldung „Dieser Termin ist nicht mehr verfügbar“ angezeigt.

9. Nicht-funktionale Anforderungen
Das System soll auf mobilen Geräten nutzbar sein.
