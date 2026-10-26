# Phasenplan — Terminplaner für die THM

Kürzel: ecib

## Studie

**Ergebnis der Phase:** …

- Die heutige Lage aufnehmen: wie Sprechstunden und Prüfungstermine bisher vereinbart werden und wo es hakt

## Systemspezifikation

**Ergebnis der Phase:** …

- Festlegen, welche Vorgänge ein KI-Agent über die API auslösen darf — z.B. freie Termine abfragen und buchen, aber keine Prüfungstermine absagen
- Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen
- Beschreiben, welche Termindaten mit dem Kalendersystem der Hochschule ausgetauscht werden

## Systemkonstruktion

**Ergebnis der Phase:** …

- Eigenentwicklung, Anpassung einer Open-Source-Lösung und Kauf nebeneinanderstellen und nach Kosten und Nutzen bewerten
- Das System in Komponenten zerlegen — z.B. Terminverwaltung, Benachrichtigung, Anmeldung — und deren Schnittstellen festlegen
- Bildschirmskizzen der Buchungsseite mit Studierenden durchgehen
- Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen
- Aufwand schätzen und einen Meilensteinplan vorschlagen
- Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten
- Datenbank, Programmiersprache und Web-Framework auswählen

## Implementierung

**Ergebnis der Phase:** …

- Die Komponente „Benachrichtigung“ programmieren
- Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen
- Die fertige Komponente „Terminverwaltung“ für sich testen, ehe sie mit anderen zusammenkommt
- Testfälle formulieren, an denen sich später zeigt, ob das System leistet, was vereinbart wurde

## Integration & Einführung

**Ergebnis der Phase:** …

- Die THM installiert das System in ihrer eigenen Umgebung und prüft es in eigener Verantwortung
- Mit Lehrenden und Sekretariaten Schritt für Schritt beschreiben, wie ein Sprechstundentermin gebucht wird
- Eine Hotline für Fragen der Anwenderinnen und Anwender besetzen
- Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen
- Probebetrieb mit einem Fachbereich, ehe die ganze Hochschule umsteigt
- Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt
- Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert

## Wartung

**Ergebnis der Phase:** …

- Einen Fehler bei der Zeitumstellung beheben, den ein Sekretariat gemeldet hat
- Eine Warteliste für ausgebuchte Termine nachrüsten, die sich die Lehrenden nach einem Semester wünschen

## Bei welchen Karten waren Sie unsicher — und was haben Sie abgewogen?

- **Terminverwaltung und Benachrichtigung zusammenführen und ihr Zusammenspiel gegen Testfälle prüfen** (Implementierung): …
- **Die API entwerfen: Endpunkte, Datenformat und die Anmeldung der KI-Agenten festlegen** (Systemkonstruktion): …
- **Aufwand schätzen und einen Meilensteinplan vorschlagen** (Systemkonstruktion): …
- **Festlegen, welche Angaben zu einem Termin gehören und wie Termine, Personen und Räume zusammenhängen** (Systemspezifikation): …
- **Mit einem technischen Prototyp prüfen, ob die Anmeldung über das Hochschulkonto funktioniert** (Integration & Einführung): …
- **Das System als Ganzes unter Federführung des Qualitätsbeauftragten gegen die Testfälle prüfen** (Integration & Einführung): …
- **Festlegen, in welcher Reihenfolge die Komponenten gebaut werden und welche Zwischenziele gelten** (Systemkonstruktion): …
- **Mit einem KI-Agenten prüfen, ob sich ein Sprechstundentermin vollständig über die API buchen lässt** (Integration & Einführung): …

<!-- zuordnung ue02-phasenplan: k01=implementierung k02=konstruktion k03=integration k04=integration k05=wartung k22=spezifikation k06=konstruktion k07=studie k08=implementierung k09=konstruktion k10=konstruktion k11=integration k12=implementierung k23=konstruktion k13=konstruktion k14=spezifikation k15=integration k16=integration k17=wartung k18=konstruktion k19=spezifikation k24=integration k20=integration k21=implementierung | unsicher: k08 k23 k13 k14 k15 k16 k18 k24 -->
