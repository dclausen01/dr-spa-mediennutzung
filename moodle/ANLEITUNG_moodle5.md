# Mediennutzung reflektieren und Medienerziehung – Moodle-Kurs von Hand einrichten

Normalerweise geht es schneller mit der Kurssicherung:
**Kurs › Mehr › Wiederverwendung › Wiederherstellen** → `dr-spa-mediennutzung_moodle5.mbz` hochladen → „In diesen Kurs, Inhalte hinzufügen“ → durchklicken. Diese Anleitung ist die Rückfallebene, falls Wiederherstellen nicht erlaubt ist.

## Vorbereitung

- Kurs › Einstellungen › **Abschlussverfolgung: Ja**
- Kursformat: Themen (Moodle 5: Unterabschnitte müssen von der Moodle-Administration aktiviert sein)

## Einstellungen für jedes Lernpaket

Aktivität **Lernpaket** (SCORM) anlegen, ZIP aus `lernpakete/` hochladen, dann:

- Darstellung: **Anzeige des Pakets: Aktuelles Fenster** · Breite 100 % · Höhe 500
- Darstellung: **Kursstruktur anzeigen: Deaktiviert** · **Navigation anzeigen: Nein** · **Struktur-Seite überspringen: Immer** · Versuchsstatus anzeigen: Nein
- Bewertung: Höchstbewertung 100, Bewertungsmethode: Höchste Bewertung
- Versuchsverwaltung: Beherrschungswert überschreibt Status: Ja
- Aktivitätsabschluss: **Bedingungen erfüllt** → **Status erforderlich: Abgeschlossen** (nur „abgeschlossen“ anhaken)
- Ausnahme Startseite und Einstufungstests: **kein Aktivitätsabschluss**; die Startseite außerdem Bewertung 0.

## Abschnitt „Allgemeines“ (ganz oben)

- Lernpaket **🧭 Mein Lernpfad – hier geht's los** – `lernpakete/dr-spa-mediennutzung_start_scorm2004.zip`
- Lernpaket **🎯 Einstufungstest: direkt zu Kinder und Medien** – `lernpakete/dr-spa-mediennutzung_einstufung-kinder-und-medien_scorm2004.zip`

## Abschnitt „🌱 Ich und Medien“

- Lernpaket **I1 · Meine Medienbiografie** – `lernpakete/dr-spa-mediennutzung_i1_scorm2004.zip`
- Lernpaket **I2 · Mein Medientag** – `lernpakete/dr-spa-mediennutzung_i2_scorm2004.zip` – Voraussetzung: „I1 · Meine Medienbiografie“ abgeschlossen
- Lernpaket **I3 · Digitales Wohlbefinden** – `lernpakete/dr-spa-mediennutzung_i3_scorm2004.zip` – Voraussetzung: „I2 · Mein Medientag“ abgeschlossen
- Lernpaket **I4 · Cybermobbing erkennen und handeln** – `lernpakete/dr-spa-mediennutzung_i4_scorm2004.zip` – Voraussetzung: „I3 · Digitales Wohlbefinden“ abgeschlossen
- Unterabschnitt **★ Meilenstein: Meine Medienreflexion** – Voraussetzung: „I4 · Cybermobbing erkennen und handeln“ abgeschlossen
  - Lernpaket **★ Meilenstein: Meine Medienreflexion – Auftrag & Checkliste** – `lernpakete/dr-spa-mediennutzung_im_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Medienreflexion abgeben** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.docx,.odt, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihre Medienreflexion hoch (ca. eine Seite). **Keine Screenshots oder Zahlen Ihrer Bildschirmzeit** – nur Ihre Gedanken. Dateiname zum Beispiel `2026-11-20 Medienreflexion_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Rückblick: nicht erreicht (0 P.) · erreicht: mindestens zwei prägende Medienerfahrungen aus der Biografie benannt (2 P.) · besonders gut: Zusammenhang zwischen früheren Erfahrungen und heutiger Nutzung erklärt (3 P.)
    - Heute: nicht erreicht (0 P.) · erreicht: eigene Nutzung beschrieben – was tut gut, was nicht (2 P.) · besonders gut: mit Erkenntnissen aus Fokus-Experiment oder Bildschirmzeit begründet (ohne Zahlen preiszugeben) (3 P.)
    - Vorsatz: nicht erreicht (0 P.) · erreicht: ein konkreter, überprüfbarer Vorsatz (2 P.) · besonders gut: mit Plan, wie er umgesetzt und überprüft wird (3 P.)
    - Vorbildrolle: nicht erreicht (0 P.) · erreicht: beschreibt, was die eigene Nutzung für die Arbeit mit Kindern bedeutet (2 P.) · besonders gut: konkrete Regel für sich als Fachkraft in Kita, OGS oder Grundschule (3 P.)

## Abschnitt „🚀 Kinder und Medien“

Voraussetzung am Abschnitt (Einschränkung: Aktivitätsabschluss bzw. Bewertung, verknüpft mit „mindestens eine“): „📤 Meilenstein: Medienreflexion abgeben“ abgeschlossen **oder** „🎯 Einstufungstest: direkt zu Kinder und Medien“ mit mindestens 80 % bewertet.

- Lernpaket **K1 · Bildungsthema „Medien und Digitalisierung“** – `lernpakete/dr-spa-mediennutzung_k1_scorm2004.zip`
- Unterabschnitt **K2 · Medien in jedem Alter** – Voraussetzung: „K1 · Bildungsthema „Medien und Digitalisierung““ abgeschlossen
  - Lernpaket **K2 · Medien in jedem Alter** – `lernpakete/dr-spa-mediennutzung_k2_scorm2004.zip`
  - Aufgabe **📤 Zwischenabgabe: Infokarte für eine Altersstufe** – Dateiabgabe, höchstens 1 Datei(en), Dateitypen .pdf,.png,.jpg, 10 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihre Infokarte aus Aufgabe 1 hoch (PDF oder Bild).
- Lernpaket **K3 · Eltern zur Mediennutzung beraten** – `lernpakete/dr-spa-mediennutzung_k3_scorm2004.zip` – Voraussetzung: „K2 · Medien in jedem Alter“ abgeschlossen
- Unterabschnitt **★ Meilenstein: Kurzberatung vorbereiten** – Voraussetzung: „K3 · Eltern zur Mediennutzung beraten“ abgeschlossen
  - Lernpaket **★ Meilenstein: Kurzberatung vorbereiten – Auftrag & Checkliste** – `lernpakete/dr-spa-mediennutzung_km_scorm2004.zip`
  - Aufgabe **📤 Meilenstein: Kurzberatung abgeben** – Dateiabgabe, höchstens 2 Datei(en), Dateitypen .pdf,.docx,.odt, 100 Punkte, Abschluss: „Abgabe erforderlich“
    Beschreibung: Laden Sie Ihren Beratungsleitfaden und Ihre Elterninfo hoch (zusammen ca. 2 Seiten, eine oder zwei Dateien). Dateiname zum Beispiel `2026-11-27 Kurzberatung Medien_Nachname,Vorname.pdf`.
    Bewertungsmethode **Bewertungsraster** mit diesen Kriterien:
    - Fallverständnis: nicht erreicht (0 P.) · erreicht: Anliegen und Situation der Familie richtig erfasst (2 P.) · besonders gut: Bedürfnisse der Eltern und des Kindes ausdrücklich berücksichtigt (3 P.)
    - Gesprächsleitfaden: nicht erreicht (0 P.) · erreicht: alle sechs Phasen mit passenden Sätzen geplant (2 P.) · besonders gut: offene Fragen und Reaktion auf mögliche Einwände vorbereitet (3 P.)
    - Fachliche Richtigkeit: nicht erreicht (0 P.) · erreicht: Empfehlung für das Alter korrekt und mit Quelle (2 P.) · besonders gut: Chancen und Risiken ausgewogen dargestellt (3 P.)
    - Wertschätzung: nicht erreicht (0 P.) · erreicht: keine Vorwürfe, Eltern entscheiden selbst (2 P.) · besonders gut: kleine, alltagstaugliche Schritte als Angebot formuliert (3 P.)
    - Elterninfo: nicht erreicht (0 P.) · erreicht: kurz, verständlich, höchstens eine Seite (2 P.) · besonders gut: barrierearm (einfache Sprache, klare Gliederung, ggf. mehrsprachig gedacht) (3 P.)

