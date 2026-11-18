# KickerTickerRecognition

Erstellt mit Python 3.15

## Beschreibung
Projekt im Rahmen des Seminars [Closed vs. Open LLMs: Status quo](https://lehre.idh.uni-koeln.de/lehrveranstaltungen/wintersemester-2026-2027/openllms-2026/), welches sich mit der zeitlichen Einordnung von Fussballtickersnippets von [kicker](kicker.de) beschäftigt.  

<img width="537" height="885" alt="grafik" src="https://github.com/user-attachments/assets/2db1437f-ad14-4a34-b5d8-235cb43dd36f" />

Arbeitsschritte: 
- Korpus beschaffen
- Prompt Engineering
- System laufen lassen
- Ergebnisse evaluieren

## Korpus
Anfrage gestellt an [Fussballlinguistik.de](https://fussballlinguistik.de/korpora/korpusdokumentation/)
-> 5325 Liveticker und 5329 Spielberichte aus den Bundesligasaisons der Männer und Frauen 2006–2023 von kicker.de
-> 86.683 Types und 11.661.402 Tokens

Alternativ eigenes Scrapping Script bauen und von jeder Zeitspanne ca. 100-200 Tickereinträge extrahieren.

## Modelle
- [gpt-oss-20b-GGUF Q4_K_M](https://huggingface.co/unsloth/gpt-oss-20b-GGUF)
- [Qwen3.8-27B-GGUF UD-IQ3_S](https://huggingface.co/unsloth/Qwen3.8-27B-GGUF)
- [gemma-4-12B](https://huggingface.co/google/gemma-4-12B)

Vergleich der verschiedenen Modelle bei der Evaluation.

## Prompts
Der Plan ist, multilinguale Prompts und verschiedene Promptsstrategien zu testen.

Stichprobenartiger Vergleich mit geschlossenen Modellen in kontrollierter Closed-Book-Umgebung geplant.

Konkrete Prompts folgen...

## Chats

## Ergebnisse


### Bewertungskriterien
 Verschiedene Klassen mit jeweils unterschiedlichen Zeitspannen.

 Einteilung gröber oder feiner je nachdem, wie gut die offenen Modelle predicten können.
