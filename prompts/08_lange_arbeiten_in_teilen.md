# 08 – Lange Arbeiten in Teilen

**Wann brauchst du das?** Selten. Aktuelle KI-Modelle verarbeiten Arbeiten von 20–40 Seiten problemlos am Stück, vor allem als angehängte Datei. Dieser Ablauf ist für Fälle gedacht, in denen die KI meldet, dass der Text zu lang ist, oder offensichtlich nur einen Teil gelesen hat (z. B. bei kostenlosen Versionen oder Abschlussarbeiten mit 80+ Seiten).

## Ablauf

**Schritt 1 – zuerst diesen Text senden:**

```text
Ich schicke dir gleich eine längere Hochschularbeit in mehreren Teilen. Bestätige jeden Teil nur mit „Teil X erhalten“ – keine Analyse, keine Zusammenfassung, keine Kommentare. Erst wenn ich „ALLE TEILE GESENDET“ schreibe, folgt meine eigentliche Anweisung.
```

**Schritt 2 – die Teile senden.** Am besten kapitelweise, jeweils beginnend mit „Teil 1 von 4:“ usw. Faustregel: höchstens 10–15 Seiten pro Teil.

**Schritt 3 – den eigentlichen Prompt senden.** Schreibe „ALLE TEILE GESENDET“ und füge direkt darunter einen Prompt aus diesem Repo ein (z. B. 00). Ersetze den Platzhalter am Ende durch:

```text
Die Arbeit hast du bereits vollständig in Teilen erhalten. Beziehe dich auf alle Teile.
```

## Plan B: kapitelweise korrigieren

Wenn die KI trotzdem den Überblick verliert:

1. Jedes Kapitel einzeln mit `03_quellen_und_zitation` und `04_sprache_und_stil` prüfen.
2. Für das große Ganze nur ein „Skelett“ an `02_struktur_und_argumentation` geben: Inhaltsverzeichnis, komplette Einleitung, komplettes Fazit und von jedem Kapitel den ersten und letzten Absatz.
3. Zum Schluss `05_abgleich_aufgabenstellung` mit demselben Skelett.
