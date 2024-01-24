---
title: Konventionen
---

# Code guidlines
    
    
## Rule of 30

- Methoden sollten nicht mehr als 30 Zeilen haben (Kommentare und Leerzeilen außen vor)
- Klassen sollten nicht mehr als 30 Mothoden haben
- Order sollten nicht mehr als 30 Klassen beinhalten
- Ein Objekt sollte nicht mehr als 30 Eigenschaften haben

## PHP

- Einhaltung des [PSR-2](https://www.php-fig.org/psr/psr-2/) Standard
- Maximale Verschachtelungstiefe von 3 innerhalb einer Funktion
- Benennungen mit PascalCase Konvention
- keinen schließenden "?>" Tag am ende von PHP Dateien
- Erste Buchstabe bei Klassen-Namen groß schreiben
- bei Methoden, Variablen, Properies wird der erste Buchstabe klein geschrieben
- geschweifte Klammern von Klassen und Methoden in seperaten Zeilen
- Methoden sollten nicht mehr als drei Parameter haben 
- 4 Leerzeichen zum einrücken nutzen, keine Tabs
- Konstanten komplett grpoß schreiben, z.B. 'STUFF_LEVEL'
- wenn nicht anders benötigt, dann einfache Anührungszeichen bei Strings
- PHP Konstanten 'true', 'false' und 'null' werden komplett klein geschrieben 

## Database

- Tabellen und Spalten werden komplett klein benannt in Snake-Case Prinzip:  'test_table', 'test_column'
- Key-Words in Statements werden groß geschrieben: 'SELECT', 'WHERE', 'JOIN', 'AND', 'LIMIT', ...

## git

- Beispiel Commit Message: '[ADD] (redesign) new header

  \#TICKETNUMMER neues Website Layout'
- Commits müssen mit einen der Folgenden Prefix starten:
    - [ADD]: add a new feature
    - [CHANGE]: change existing code and behavior
    - [REVIEW]: change code, but not behavior, typically when cleanup code
    - [REMOVE]: remove code
- Optional: nach dem Prefix folgt in Klammern das Topic zu dem der Commit gehört
- er folgt eine Beschreibung des Commits#
- wenn ein Ticket zugeordnet ist, folgt nach einer Leerzeile die TIcketnummer und Name des Tickets