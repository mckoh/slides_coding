# Ablauf

### **Block 1: Grundlagen & Abgrenzung (00:00 – 00:50 | 50 Min.)**

**Ziel:** Scripting vs. Programmierung, Sprachentypen und Paradigmen einordnen.

- **Frontal / Folien (ca. 15 Min.):**
    - **Folie 1:** Kursüberblick (6 Termine) & Zielbild der heutigen Einheit.
    - **Folie 2:** Übersicht: Markup (HTML/XML) vs. Scripting (Python/JS) vs. System-Programmierung (C/C++).
    - **Folie 3:** Die 2 großen Paradigmen: Imperativ (*Wie* macht man es?) vs. Deklarativ (*Was* soll das Ergebnis sein?).
- **Live-Coding / LLM-Interaktion (ca. 35 Min.):**
    - *Dozent-Prompt:*

        > "Erkläre den Unterschied zwischen imperativer und deklarativer Programmierung anhand eines alltäglichen Beispiels (z. B. Zubereitung von Kaffee oder Sortieren von Wäsche) und zeige dazu je ein kurzes Code-Beispiel in Python (imperativ) und SQL (deklarativ)."
        >
    - *Gemeinsames Erarbeiten & Nachfragen:*

        > **Nachfrage:** "Was passiert, wenn wir die Reihenfolge der Befehle im imperativen Beispiel ändern? Warum ist das im deklarativen Beispiel egal?" **Nachfrage:** "Welchen Ansatz verfolgt eine HTML-Datei: Ist HTML eine Programmiersprache? Lass uns das kritisch hinterfragen."
        >

### **Block 2: Formale vs. Natürliche Sprache (00:50 – 01:40 | 50 Min.)**

**Ziel:** Syntax, Semantik, Formalisierung und die Übersetzung in Maschinencode verstehen.

- **Frontal / Folien (ca. 15 Min.):**
    - **Folie 4:** Natürliche Sprache (Kontext, Toleranz, Ambiguität) vs. Formale Sprache (Exaktheit, Syntaxfehler).
    - **Folie 5:** Vom Quelltext zum Bitstream: Compiler (AOT) vs. Interpreter (JIT / Bytecode).
    - **Folie 6:** Der "Sprachen-Zoo": Warum gibt es hunderte Programmiersprachen? (Performance, Domäne, Zielplattform).
- **Live-Coding / LLM-Interaktion (ca. 35 Min.):**
    - *Dozent-Prompt:*

        > "Simuliere einen extrem pedantischen Python-Interpreter. Ich gebe dir einen Satz in deutscher Sprache und einen einfachen Python-Code mit einem Syntaxfehler. Zeige mir bei beidem exakt auf, wo das Missverständnis entsteht und warum der Computer im Gegensatz zum Menschen keine Ambiguität toleriert."
        >
    - *Gemeinsames Erarbeiten & Nachfragen:*

        > **Nachfrage:** "Nimm den folgenden Python-Code und zeige mir Schritt für Schritt, wie ein Interpreter ihn Zeile für Zeile ausführt, im Vergleich dazu, wie ein C-Compiler den gesamten Code vorab in Maschinencode übersetzt." **Nachfrage:** "Generiere eine Gegenüberstellung von C, Python und JavaScript für die Ausgabe 'Hello World'. Warum braucht C dafür 5 Zeilen und Python nur eine?"
        >

### **PAUSE (01:40 – 02:00 | 20 Min.)**

### **Block 3: Das Lasagne-Prinzip – Algorithmen & Qualität (02:00 – 02:50 | 50 Min.)**

**Ziel:** Verstehen, was ein Algorithmus ist, wie er implementiert wird und was guten Code von schlechtem Code unterscheidet.

- **Frontal / Folien (ca. 15 Min.):**
    - **Folie 7:** Das Lasagne-Analogie-Poster: Rezept (Algorithmus) vs. Gekochte Lasagne (Implementierung).
    - **Folie 8:** Algorithmen lösen *Klassen* von Problemen (z. B. "Sortiere alles", nicht nur "Sortiere diese 3 Zahlen").
    - **Folie 9:** Qualitätsmerkmale von Code: Eleganz/Einfachheit vs. Wartbarkeit, Integrierbarkeit und Robustheit.
- **Live-Coding / LLM-Interaktion (ca. 35 Min.):**
    - *Dozent-Prompt:*

        > "Schreibe ein Rezept für Lasagne in Form eines formalen Algorithmus in Pseudocode. Berücksichtige dabei Schleifen (z. B. 'für jede Schicht'), Bedingungen (z. B. 'wenn Käse braun, dann rausnehmen') und Fehlerbehandlung (z. B. 'wenn Nudelplatten trocken, mehr Soße')."
        >
    - *Gemeinsames Erarbeiten & Nachfragen:*

        > **Nachfrage:** "Dieser Pseudocode ist elegant für Menschen zu lesen. Übersetze ihn nun in eine produktionsreife Python-Funktion inklusive Type-Hints, Error Handling und Docstrings. Zeige, worauf es bei Wartbarkeit ankommt." **Nachfrage:** "Refactore den Code: Mach ihn so kurz wie möglich (Golfing) und danach so lesbar wie möglich. Diskutiere den Unterschied bezüglich Eleganz vs. Wartbarkeit."
        >

### **Block 4: Der Alltag in der Softwareentwicklung (02:50 – 03:30 | 40 Min.)**

**Ziel:** Das Ökosystem verstehen – Core, Libraries, Package Management, Git und KI-Unterstützung.

- **Frontal / Folien (ca. 15 Min.):**
    - **Folie 10:** Die Pyramide: Sprachkern → Standardbibliothek → Drittanbieter-Pakete (PyPI/npm).
    - **Folie 11:** Werkzeuge der Entwickler: Paketverwaltung, Git/GitHub (Historisierung & Collaboration).
    - **Folie 12:** Die neue Rolle von KI in der Softwareentwicklung (Vom Tippen zum Nachdenken & Reviewen).
- **Live-Coding / LLM-Interaktion (ca. 25 Min.):**
    - *Dozent-Prompt:*

        > "Ich möchte in Python ein Diagramm zeichnen. Zeige mir zuerst, wie das nur mit Python-Bordmitteln ginge (oder warum das schwer ist), und danach, wie man es mit einer externen Bibliothek wie matplotlib in 3 Zeilen löst. Erkläre dazu kurz das Prinzip eines Package Managers wie pip."
        >
    - *Gemeinsames Erarbeiten & Nachfragen:*

        > **Nachfrage:** "Simuliere ein Code-Review: Ich gebe dir folgenden Python-Schnipsel. Kritisiere ihn wie ein Senior Developer hinsichtlich Benennung, Struktur und Sicherheit." **Nachfrage:**"Wie verändert der Einsatz von LLMs wie dir die tägliche Arbeit von Entwicklern? Was müssen Entwickler heute können, was ein LLM nicht übernehmen kann?"
        >