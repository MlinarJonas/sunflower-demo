# Sonnenblume: Mathematik der Spiralen

Interaktive Web-Demonstration zur Frage, warum man auf Sonnenblumen Fibonacci-Zahlen von Spiralen zählt. In vier kurzen Stationen bauen Betrachtende eine Blüte Punkt für Punkt nach und entdecken den Zusammenhang zwischen Brüchen, Rekorden der Annäherung und dem goldenen Winkel.

**Zur Seite:** https://mlinarjonas.github.io/sunflower-demo/

Version 1.0, November 2026 · Deutsch und Englisch · läuft im Browser, ohne Installation

---

## Für wen

Für Maturandinnen und Maturanden mit gutem mathematischem Grundverständnis, im Selbststudium oder im Unterricht am Beamer. Der ganze Pfad dauert geschätzt 15 bis 20 Minuten.

## Inhalt

| Station | Thema | Kernaussage |
|---|---|---|
| E1 Brüche geben Strahlen | gleicher Drehwinkel, Punkt für Punkt | Ein gekürzter Bruch p/q als Drehung gibt genau q Strahlen. |
| E2 Fast-Brüche geben Spiralen | Drehung knapp neben einem Bruch | Die q Strahlen biegen sich zu q Spiralarmen. |
| E3 Rekorde | wann q Schritte fast eine ganze Umdrehung ergeben | Der nächste Nachbar weiter aussen liegt immer um einen Rekordhalter weiter; beim goldenen Winkel sind das Fibonacci-Zahlen. |
| E4 Die Sonnenblume | Spiralen zählen, Vergleich mit dem Lucas-Winkel | Die Spiralzahlen sind die Rekordhalter des goldenen Winkels. |
| Quellen und Methoden | Modell, Zählregel, Belege | was bewiesen, zitiert oder nur beobachtet ist |

Jede Station folgt demselben Ablauf: Frage, Vorhersage, Erkunden, Erklärung, Merksatz. Vertiefungen lassen sich unter "Genauer hingeschaut" aufklappen.

## Bedienung

- **Stationen wählen:** Kopfzeile (E1 bis E4, Quellen und Methoden) oder der Knopf unten rechts.
- **Innerhalb einer Station:** "Weiter" und "Zurück" in der rechten Spalte.
- **Vorhersagen:** Eine Antwort anklicken. Sie wird nicht bewertet, nur angezeigt; danach erscheint das Bild.
- **Sprache:** DE oder EN oben rechts. Die Station bleibt beim aktuellen Schritt.
- **Direktlinks:** `#E1` bis `#E4` und `#Q` springen zu einer Station, `#E3:4` zu einem bestimmten Schritt (Zählung ab 0).

### Tastatur

| Wo | Taste | Wirkung |
|---|---|---|
| überall | Tab, Enter, Leertaste | Element wählen und auslösen |
| E1 | Leertaste | Abspielen und anhalten |
| E1 | Pfeiltasten am Regler | Punktzahl N ändern |
| E2 | Pfeiltasten am Regler | Abweichung um 0.0001 ändern |
| E2 | Umschalt + Pfeil, Taste 0 | um 0.001 ändern, auf null setzen |
| E3, Lupe | Pfeiltasten, Bild auf / Bild ab | anderer Punkt: ±1, ±50 |
| E4 | Pfeiltasten am Regler | Ring verschieben |
| E4 | G, L | goldener Winkel, Lucas-Winkel |

## Darstellung und Belege

- Jedes Bild trägt ein Kennzeichen. "Berechnet" heisst: genau so gerechnet, wie der Text es beschreibt, ohne Verschönerung. Vergrösserte Ausschnitte sind als solche markiert.
- Die Seite unterscheidet Bewiesenes, Zitiertes und am Computer Beobachtetes. Die Einzelheiten stehen auf der Seite "Quellen und Methoden".
- Alle Rechnungen sind mit automatischen Tests geprüft und von einem unabhängigen Python-Programm nachgerechnet.

## Technik und Datenschutz

- Statische Seite, gebaut mit Vite und TypeScript; Zeichnungen mit Canvas und SVG, Formeln mit KaTeX.
- Keine Analyse, keine Cookies, keine externen Schriften oder Skripte. Gespeichert wird nur die gewählte Sprache, und zwar im eigenen Browser.
- Ausgelegt für Laptop und Beamer ab 1280 × 720; geprüft in Microsoft Edge.
- Dieses Archiv enthält nur die fertige Seite. Quellcode, Tests und Projektdokumentation liegen in einem privaten Archiv.

## Entstehung

Diese Seite hat Jonas Mlinar im Leistungsnachweis "Maturarbeiten betreuen" an der PH Bern (HS 25) erstellt. Sie ist ein Testlauf dafür, wie Maturandinnen und Maturanden einen Coding Agent in einer Maturaarbeit einsetzen können. Den Code hat ein Coding Agent geschrieben (Claude von Anthropic). Die Entscheidungen und die Freigabe der Texte und Beweise lagen beim Verfasser.

## Quellen

1. P. Alessandri, V. Berthé: Three distance theorems and combinatorics on words. *L'Enseignement Mathématique* 44 (1998), 103 bis 132.
2. A. Hurwitz: Ueber die angenäherte Darstellung der Irrationalzahlen durch rationale Brüche. *Mathematische Annalen* 39 (1891), 279 bis 284. [doi:10.1007/BF01206656](https://doi.org/10.1007/BF01206656)
3. I. Niven: A simple proof that π is irrational. *Bulletin of the American Mathematical Society* 53 (1947), 509. [doi:10.1090/S0002-9904-1947-08821-2](https://doi.org/10.1090/S0002-9904-1947-08821-2)
4. I. Short: Ford circles, continued fractions, and best approximation of the second kind. [arXiv:0912.1997](https://arxiv.org/abs/0912.1997) (2009).
5. J. Swinton, E. Ochu, The MSI Turing's Sunflower Consortium: Novel Fibonacci and non-Fibonacci structure in the sunflower. *Royal Society Open Science* 3 (2016), 160091. [doi:10.1098/rsos.160091](https://doi.org/10.1098/rsos.160091)

## Rechte

© 2026 Jonas Mlinar. Alle Rechte vorbehalten. Die Seite enthält die Bibliotheken KaTeX und marked unter der MIT-Lizenz; die Lizenztexte stehen in [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md).

---

## In English

An interactive web demonstration of why sunflowers show Fibonacci numbers of spirals. Four short stations (fractions make rays, almost-fractions make spirals, records, the sunflower) plus a page on sources and methods. Available in German and English; choose EN at the top right. Runs in any current browser without installation and collects no data. Every picture is labelled ("computed"), and the site distinguishes what is proved, cited or only observed on the computer. Made by Jonas Mlinar for a course on supervising upper secondary final projects at PH Bern; the code was written by a coding agent (Claude by Anthropic).

**Open the site:** https://mlinarjonas.github.io/sunflower-demo/
