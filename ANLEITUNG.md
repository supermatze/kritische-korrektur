# Anleitung

## Grundablauf

1. **Prompt kopieren:** Datei in `prompts/` öffnen und oben rechts im grauen Kasten auf das Kopier-Symbol klicken.
2. **Neuen Chat starten.** Nicht den Chat, in dem du an der Arbeit geschrieben hast (siehe unten).
3. **Kontext ausfüllen:** Alles, was du weißt; Unbekanntes einfach leer lassen. Am wichtigsten ist die Aufgabenstellung im Wortlaut.
4. **Arbeit anhängen** (PDF oder DOCX) oder den Text am Ende des Prompts einfügen.
5. **Gutachten abarbeiten:** Am besten entlang des Überarbeitungsplans am Ende. Danach mit `07_zweite_runde` prüfen.

## So holst du mehr heraus

**Immer ein neuer Chat.** Hat die KI im selben Chat schon beim Schreiben geholfen, bewertet sie den Text oft milder, weil sie ihre eigenen Vorschläge mitbeurteilt.

**Aufgabenstellung wörtlich.** Die häufigste Ursache für schlechte Noten ist nicht schlechtes Schreiben, sondern eine Arbeit, die an der Aufgabe vorbeigeht. Das kann die KI nur prüfen, wenn sie die Aufgabe kennt.

**Bewertungskriterien und Leitfaden mitschicken.** Erwartungshorizont, Rubrik oder Zitierleitfaden des Instituts als Datei anhängen. Die Prompts geben diesen Vorgaben Vorrang.

**Datei statt Copy-Paste.** Beim Kopieren aus Word gehen Fußnoten, Tabellen und Formatierung oft verloren. Bei Fußnoten-Zitierweise heißt das: Die KI sieht deine Belege gar nicht und meldet überall „Beleg fehlt“. Lieber PDF anhängen.

**Module für Tiefe.** Die Vollkorrektur deckt alles ab, geht bei langen Arbeiten aber zwangsläufig weniger ins Detail. Für Zitation (03) und Sprache (04) lohnen sich die Einzelmodule zusätzlich.

**Zweitmeinung.** Denselben Prompt in einer zweiten KI laufen lassen. Was beide finden, ist fast sicher ein echtes Problem.

## Nachfrage-Prompts

Nach einem Gutachten lohnen sich diese Nachfragen im selben Chat.

Wenn das Feedback zu freundlich wirkt:
```text
Sei strenger. Was würde eine sehr kritische Prüfer:in außerdem bemängeln, das du noch nicht genannt hast?
```

Um Wichtiges von Geschmack zu trennen:
```text
Welche deiner Kritikpunkte würden sicher Punkte kosten, und welche sind eher Geschmackssache?
```

Um einen Befund zu verstehen:
```text
Erkläre Befund W2 genauer und zeig mir an einem einzelnen Satz aus meinem Text, wie eine bessere Version aussehen könnte.
```

Um gezielt nachzuprüfen:
```text
Ich habe Kapitel 3 überarbeitet: [Text]. Ist K1 damit behoben? Wenn nicht: Was fehlt noch?
```

Wenn du anderer Meinung bist:
```text
Bei Befund W4 sehe ich das anders, weil … Überzeugt dich das? Bleib bei deiner Einschätzung, wenn mein Argument nicht trägt.
```

Kurz vor der Abgabe:
```text
Welche Stellen sollte ich vor der Abgabe noch einmal an den Originalquellen prüfen, weil du sie nicht verifizieren konntest?
```

## Grenzen

- **Quellen:** Die KI kann nicht überprüfen, ob ein Zitat auf der angegebenen Seite steht oder ob eine Quelle so existiert. Literaturvorschläge immer selbst prüfen – KI-Modelle erfinden manchmal plausibel klingende Titel.
- **Fachliche Tiefe:** In Spezialthemen kann die KI fachliche Fehler übersehen oder selbst falsch liegen. Dein Fachwissen und deine Betreuung haben Vorrang.
- **Noten:** Die Schätzung ist eine Orientierung. Jede Prüfer:in gewichtet anders.
- **Kein Plagiatsscanner:** Verdachtsstellen sind Hinweise, keine Prüfung.
- **Schwankungen:** Zwei Durchläufe liefern nicht exakt dasselbe. Befunde, die wiederholt auftauchen, sind die verlässlicheren.

## Regeln und Datenschutz

- Schau in die Prüfungsordnung oder die Kursvorgaben, ob und wie KI genutzt werden darf und ob du die Nutzung angeben musst.
- Lade keine personenbezogenen Daten hoch, zum Beispiel nicht anonymisierte Interviews oder Namen von Befragten.
- Prüfe in den Einstellungen deines KI-Tools, ob deine Inhalte zum Training verwendet werden, und schalte das bei Bedarf ab.

## Repo anpassen

- **Eigene Gewichtung:** in `prompts/00_vollkorrektur.md` im Abschnitt „Orientierung Noten“ ändern.
- **Kursvorlagen:** Für wiederkehrende Kurse eine Kopie des Prompts mit fest ausgefülltem Kontext anlegen, z. B. `prompts/kurse/soziologie_hausarbeit.md`.
- **Erfahrungswerte:** Was eine bestimmte Dozentin oder ein Dozent immer bemängelt, gehört in den Kontext unter „Mir ist besonders wichtig“.
