ASCII → Binary Converter

Ein moderner, responsiver ASCII-zu-Binär-Konverter, entwickelt mit HTML, CSS und Vanilla JavaScript.
Das Projekt kombiniert ein minimalistisches Glassmorphism-Design mit einer klar strukturierten Umwandlungslogik.

⸻

Funktionen
	•	Umwandlung von ASCII-Text in 8-Bit-Binärdarstellung
	•	Responsives Layout für Desktop, Tablet und mobile Geräte
	•	Sofortige Ausgabe ohne Seitenneuladen
	•	Eingabevalidierung:
	•	Leere Eingaben werden abgefangen
	•	Reine Zahleneingaben werden als ungültig markiert

⸻

Technische Funktionsweise

Die Umwandlung erfolgt in drei Schritten:
	1.	Zeichen → numerischer Zeichencode
      mit: char.charCodeAt(0)
  2.	Dezimalzahl → Binärdarstellung
      mit: number.toString(2)
  3.	Formatierung auf 8 Bit
      mit: padStart(8, '0')

Technologien
	•	HTML5
	•	CSS3 (Glassmorphism, Responsive Layout)
	•	Vanilla JavaScript

Es werden keine externen Bibliotheken oder Frameworks verwendet.

Lizenz

Freie Nutzung zu Lern- und Demonstrationszwecken.
