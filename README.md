# Vom Token zum Agenten

**KI für Entwickler – von den Grundlagen bis zum Harness**

Ein deutschsprachiger Podcast für Softwareentwicklerinnen und -entwickler: wie Sprachmodelle funktionieren, wie man sie aus dem eigenen Code nutzt und was einen KI-Agenten zuverlässig und sicher macht. 41 kurze Folgen von 4 bis 10 Minuten, aufeinander aufbauend, ohne Mathe.

## Wer spricht

- **Jana** – die Expertin. Erklärt mit Bildern aus der Softwareentwicklung, ruhig und mit Augenzwinkern.
- **Tom** – Entwickler ohne KI-Erfahrung. Stellt die Fragen, die du auch hättest, und hakt nach.

Die Stimmen von Jana und Tom sind KI-generiert.

## Hören

Der RSS-Feed zum Abonnieren in der Podcast-App folgt in Kürze hier.

## Kernpfad für Eilige

Die mit ⭐ markierten Folgen bilden den Kernpfad: Wer nur sie hört, bekommt den roten Faden vom Token bis zum Agenten.

## Folgen

### Auftakt

- **00 · Trailer: Worum es geht** ⭐  
  Wer spricht, für wen die Reihe ist, die acht Staffeln als Landkarte, der Kernpfad und das Ticket, das uns durch die Reihe begleitet

### Staffel 1 · Was ist KI überhaupt?

*Was ist KI – und was ist an generativer KI neu?*

- **01 · Regeln schreiben oder Regeln lernen lassen** ⭐  
  KI als Sammelbegriff, Regeln schreiben gegen Machine Learning, Modell und Gewichte, Training und Inferenz, Overfitting
- **02 · Neuronale Netze und Deep Learning**  
  Neuronen und Schichten als Kette von Funktionen, warum Deep Learning Merkmale selbst findet und warum das Modell eine Black Box ist
- **03 · Klassisches ML oder generative KI?**  
  Entscheiden gegen Erzeugen, Foundation Models und warum klassisches Machine Learning für klare Aufgaben oft die bessere Wahl ist
- **04 · Die Familie der generativen Modelle**  
  Sprachmodelle, Diffusionsmodelle, GANs und multimodale Modelle im Überblick

### Staffel 2 · Wie ein Sprachmodell tickt

*Wie funktioniert ein Sprachmodell – und warum verhält es sich manchmal so seltsam?*

- **05 · Tokens – die Währung der KI** ⭐  
  Was Tokens sind, wie Text zerlegt wird und warum Kosten, Limits und Buchstabenzählen davon abhängen
- **06 · Next-Token-Prediction – der ganze Trick** ⭐  
  Wie ein Sprachmodell Text Token für Token erzeugt, warum das mehr ist als Autovervollständigung und warum es nichts nachschlägt
- **07 · Temperatur und Sampling – warum KI nie gleich antwortet**  
  Sampling, Temperatur und Top-p, warum selbst Temperatur null nicht garantiert reproduzierbar ist und was das für Tests heißt
- **08 · Transformer und Attention**  
  Die Architektur hinter allen Sprachmodellen: Attention, Parallelität und Tokens als Zahlenreihen – ohne Mathe
- **09 · Vom Rohmodell zum Assistenten**  
  Pre-Training und Base Model, Instruction Tuning, bestärkendes Lernen aus Bewertungen und der Knowledge Cutoff
- **10 · Halluzinationen** ⭐  
  Warum Sprachmodelle plausibel Falsches erzeugen, erfundene APIs und Pakete und welche Gegenmittel es gibt

### Staffel 3 · Vom Chat zur API

*Wie nutze ich ein Modell aus meinem Code – und was heißt das für meine KI-Werkzeuge?*

- **11 · Was ein Chatbot wirklich ist** ⭐  
  Modell und Produkt, die zustandslose API, der Nachrichtenverlauf als Gedächtnis und die Rollen im Gespräch
- **12 · Das Kontextfenster** ⭐  
  Wie viel ein Modell auf einmal sieht, was das kostet, warum mehr nicht besser ist und was Prompt Caching bringt
- **13 · Prompting für Entwickler** ⭐  
  Systemprompt, Zero- und Few-Shot, Chain of Thought und der Prompt als Spezifikation
- **14 · Strukturierte Ausgaben – das Modell als Funktion**  
  JSON-Schema und Structured Outputs: wie ein Modellaufruf zur typisierten Funktion im eigenen Code wird
- **15 · Testen, wenn nichts deterministisch ist: Evals**  
  Evals als Testsuite für Verhalten, die wichtigsten Bewertungsarten und Regressionen messen wie in der CI
- **16 · Welches Modell nehme ich?**  
  Reasoning-Modelle, große und kleine Modelle, proprietär oder Open-Weight – und entscheiden mit eigenen Evals

### Staffel 4 · Eigenes Wissen ins Modell

*Wie bekommt das Modell unser Wissen – und welcher Weg passt wann?*

- **17 · Das Wissensproblem und drei Wege**  
  Warum das Modell unsere Daten nicht kennt und die drei Wege: alles in den Kontext, RAG und Fine-Tuning
- **18 · Embeddings – Suchen nach Bedeutung**  
  Text als Vektor, semantische Nähe und Ähnlichkeitssuche mit Embedding-Modellen
- **19 · RAG Schritt für Schritt**  
  Chunking, Vektordatenbank, hybride Suche, Reranking und Quellenangaben – und wie man misst, ob RAG trifft
- **20 · Fine-Tuning und seine Grenzen**  
  Wann Nachtrainieren hilft, wann nicht – und warum RAG Wissen gibt und Fine-Tuning Verhalten

### Staffel 5 · Vom Chatbot zum Agenten

*Wie wird aus einem Modell, das antwortet, ein Agent, der handelt?*

- **21 · Tool Use – das Modell ruft Funktionen auf** ⭐  
  Werkzeugliste, strukturierte Aufrufe und warum immer dein Code ausführt, nie das Modell
- **22 · Der Agent Loop** ⭐  
  Die Schleife aus Fragen, Ausführen und Beobachten, Abbruchbedingungen und die Formel: ein Modell in einer Schleife mit Werkzeugen
- **23 · Workflow oder Agent?**  
  Feste Abläufe gegen eigene Entscheidungen des Modells – und die Regel: so einfach wie möglich
- **24 · MCP – der Standardstecker für Werkzeuge**  
  Das Model Context Protocol: Client, Server und Werkzeuge, die erst bei Bedarf geladen werden
- **25 · Coding-Agenten im Alltag** ⭐  
  Autonomiegrade von der Autovervollständigung bis zum Agenten, was ein Coding-Agent darf und was Computer Use ist

### Staffel 6 · Was kann schiefgehen?

*Welche neuen Risiken entstehen, wenn KI liest, schreibt und handelt?*

- **26 · Prompt Injection** ⭐  
  Versteckte Anweisungen in fremden Inhalten, direkt und indirekt, die Abgrenzung zum Jailbreak und warum das so schwer abzuwehren ist
- **27 · Datenabfluss und die Lethal Trifecta**  
  Private Daten, fremde Inhalte und Kommunikation nach außen: wie Daten abfließen und was Tool Poisoning ist
- **28 · KI-generierter Code und die Lieferkette** ⭐  
  Erfundene Pakete, unsichere Muster, Geheimnisse im Kontext – und warum Review Pflicht bleibt
- **29 · Bonus: Regeln in fünf Minuten**  
  Shadow AI, Datenschutz, Urheberrecht an generiertem Code, AI Act und DORA – nur angerissen

### Staffel 7 · Der Harness

*Was macht einen Agenten zuverlässig und sicher?*

- **30 · Agent = Modell + Harness** ⭐  
  Was der Harness ist, warum er oft mehr bringt als ein besseres Modell und die vollständige Formel der Reihe
- **31 · Context Engineering** ⭐  
  Welche Information wann im Kontext steht: schreiben, auswählen, komprimieren und isolieren
- **32 · Context Rot und Compaction**  
  Warum volle Kontexte schlechter werden und wie Zusammenfassen und Kürzen helfen
- **33 · Gedächtnis und Skills**  
  Kurz- und Langzeitgedächtnis, Projektdateien für Agenten, Skills – und manipulierte Regeldateien als Risiko
- **34 · Berechtigungen, Sandbox, Hooks und Guardrails**  
  Nur nötige Rechte, abgeschottete Umgebungen, fest programmierte Eingriffspunkte und Schutz in mehreren Schichten
- **35 · Human in the Loop und Verifikation** ⭐  
  Freigaben durch Menschen, Tests und Linter als Rückmeldung und ein Modell als Prüfer
- **36 · Praxis: Du bist Teil des Harness** ⭐  
  Aufgaben klein schneiden, erst planen, Kontext pflegen, Tests als Abnahme und Review wie bei Kollegen

### Staffel 8 · Skalieren und beobachten

*Wie verteilt man große Aufgaben auf mehrere Agenten – und behält trotzdem den Überblick?*

- **37 · Sub-Agenten** ⭐  
  Eigener, frischer Kontext für Teilaufgaben, Parallelisierung und wann sich Sub-Agenten lohnen
- **38 · Multi-Agenten-Systeme und Orchestrierung**  
  Rollen, Orchestrator und Worker, Übergaben, Kosten – und warum mehr Agenten nicht automatisch besser sind
- **39 · Agenten beobachten: Traces und Agenten-Evals**  
  Jeden Schritt aufzeichnen, ganze Abläufe bewerten und Benchmarks richtig einordnen

### Finale

- **40 · Ein Agent bearbeitet Ticket 4711 – alles zusammen** ⭐  
  Ein kompletter Agentenlauf, Schritt für Schritt, mit allen Begriffen der Reihe

## Lizenz

Inhalte: [Creative Commons Namensnennung 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.de) – frei nutzbar und weitergebbar mit Nennung „Vom Token zum Agenten / bitweise“.
