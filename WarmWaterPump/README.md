## Plan 
Prämisse des Nutzers
	- Pumpe soll nicht nach "Gefühl per Hand geschaltet werden".
Anforderungen
	- Controller soll das händische Schalten der Pumpe automatisieren.
	- Möglichst viel Solar-Warmwasser nutzen.
	- Möglichst wenig Gas verbrauchen.
	- Automatik und Manuellem Modus. 
		○ Im manuellen Modus kann über einen Knopfdruck die Pumpe aktiviert und deaktiviert werden.
		○ Im Automatikmodus schaltet die Pumpe nach definierten Regeln
	- Controller soll die Temperatur im Tank untern t_0 ermitteln
	- Controller soll die Temperatur im Tank oben t_1 ermitteln
	- Definierte Regeln im Automatikbetrieb (siehe Funktions-Planung)
	- Einstellbare Schwellwerte für Pumpenreglung
		○ Default Schwellwert t_1_max = 60 C
		○ Default Schwellwert t_0_max = 85 C
	- Der Gesamtstatus des Systems ist dem Nutzer darzustellen
		○ Temperatur aktuell t_0 & t_1
		○ Eingestellte Schwellwerte t_0_min, t_0_max & t_1_max, t_1_max
		○ Pumpe an/aus
		○ Betriebsmodi
	- System im geschlossenem Gehäuse
	- Externen Peripherien über Kupplungen angeschlossen
		○ Sensoren über Federstecker
		○ Pumpe über Schutz-Kontakt-Stecker
## Do

## Check 

## Act 
