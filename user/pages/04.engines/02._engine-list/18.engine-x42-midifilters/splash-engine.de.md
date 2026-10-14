---
title: x42 MIDI-filters
media_order: x42-midifilter.jpg
description: Eine leistungsstarke Sammlung einfacher MIDI-Filter und Tools
taxonomy:
  category:
  - effect
  tag:
  - free-software
  - ucase-kb
  - ucase-pr
  - effect
  - fx-midi
date: 17:38 24-04-2020
subtitle: Leistungsstarke Sammlung einfacher MIDI-Filter & Tools
splash:
  bg_image_landscape: x42-midifilter-hero.jpg
  bg_image: x42-midifilter-hero_small.jpg
media_thumb: x42-midifilter.jpg
urls:
- urlLink: http://x42-plugins.com/x42/x42-midifilter
  urlLabel: x42 MIDI-filter's Website
- urlLink: https://github.com/x42/x42-plugins
  urlLabel: Source Code
---
Eine Sammlung von über 25 MIDI-Datenfiltern im LV2-Plugin-Format, entwickelt und gepflegt von [Robin Gareus](http://x42-plugins.com). Die Filter folgen diesen grundlegenden Regeln:
+ Ein MIDI-Eingang, ein MIDI-Ausgang (keine Generatoren, keine Synths)
+ Keine benutzerdefinierte GUI, nur Steuereingänge
+ Jeder Regler kann automatisiert werden, die Plugins verarbeiten dynamische Parameteränderungen
+ Alle Plugins melden ihre Latency an den Host (bei den meisten beträgt sie null)
+ DRY (Don't Repeat Yourself-Prinzip) - einfache Filter, die in einem Netzwerk kombiniert werden können
+ Selbstdokumentierend: Integrierte Beschreibung und Dokumentation der Steuerungsports

##Übersicht
**CC2Note:** MIDI-Control-Change-Nachrichten in Note-on/off-Nachrichten umwandeln. Note off wird 10 ms später in die Warteschlange gestellt..

**MIDI-Kanalfilter:** Ein einfacher MIDI-Kanalfilter. Nur Daten für ausgewählte Kanäle dürfen passieren. Dieser Filter wirkt sich nur auf midi-data aus, die kanalrelevant ist (d. h. Note-On/Off, Control- und Program Changes, Key- und Channel Pressure sowie Pitchbend). MIDI-SYSEX- und Realtime-Nachrichten werden immer durchgelassen. Dieses Plugin ist für den Live-Einsatz und die Tastensteuerung vorgesehen. Siehe auch den Filter „MIDI Channel Map“..

**MIDI-Kanalzuordnung:** Midi-Kanalnummer neu schreiben. Dieser Filter wirkt sich nur auf MIDI-Daten aus, die kanalrelevant sind (d. h. Note-on/off, Control- und Program Changes, Key- und Channel Pressure sowie Pitchbend). MIDI-SYSEX- und Realtime-Nachrichten werden immer unverändert durchgeleitet..

**MIDI-Skala erzwingen:** Filtert Note-on/off-Ereignisse abhängig von der musikalischen Tonleiter. Wenn die Tonart geändert wird, werden Note-off-Ereignisse für alle aktiven tonartfremden Noten gesendet..

**MIDI Event-Filter:** Notch-style-Nachrichtenfilter. Bestimmte Nachrichten unterdrücken. Für einen flexiblen Note-on/off-Bereich siehe auch 'keyrange' und 'velocityrange'.

**MIDI-Tastenbereichsfilter:** Dieser Filter ermöglicht es, einen Bereich zulässiger MIDI-Noten festzulegen. Note-on/off-Ereignisse außerhalb des zulässigen Bereichs werden verworfen. Ändert sich der Bereich, werden Note-off-Ereignisse für aktuell aktive Noten gesendet, die dadurch außerhalb des gültigen Bereichs liegen..

**MIDI Keysplit:** Ändere die midi-Kanalnummer abhängig von der Note. Das Plugin verfolgt transponierte midi-Noten und sendet gegebenenfalls entsprechende note-off-Ereignisse, wenn der Bereich geändert wird, selbst wenn eine Note aktiv ist. Der split-point und die Kanalzuweisungen für jedes Manual sollten jedoch nur geändert werden, wenn gerade keine Noten gespielt werden..

**MapCC:** Eine Steuernachricht in eine andere umwandeln -- mit scalecc kombinieren, um den tatsächlichen Wert zu ändern/skalieren.

**MIDI-Tasten transponieren:** Flexible 12-Ton-Zuordnung. Ermöglicht, eine Note innerhalb einer Oktave einer anderen Note im selben Oktavbereich von +- 12 Halbtönen zuzuordnen. Alternativ können Noten auch maskiert (deaktiviert) werden. Wenn zwei Tasten derselben Note zugeordnet sind, werden die entsprechenden Note-on-/Events verriegelt: Nur das erste Note-on und das letzte Note-off werden gesendet. Die Einstellungen können dynamisch geändert werden: Note-on/off-Events werden entsprechend gesendet.

**MIDI-Akkord:** Harmonizer - bildet Akkorde aus einer einzelnen (Grund-)Note in einer vorgegebenen Tonleiter. Die Tonleiter sowie die Intervalle können frei automatisiert werden (aktuell gehaltene Akkorde ändern sich). Note-ons werden gehalten, bei mehreren/kombinierten Akkorden wird für die Dauer der kombinierten Akkorde nur ein einzelnes Note-on/off ausgelöst. Wird eine Note außerhalb der Tonleiter eingegeben, wird sie durchgeleitet - es wird kein Akkord zugewiesen. Hinweis: Kombiniere diesen Effekt mit dem 'MIDI
„Enforce Scale“-Filter, um sie auszusortieren.

**MIDI Delayline:** MIDI-Delay-Line. Verzögert alle MIDI-Events um eine vorgegebene Zeit, die in BPM und Beats angegeben wird. Wenn die Verzögerung einen Zufallsfaktor enthält, sorgt dieser Effekt dafür, dass Note-On-/Note-Off-Events unabhängig von der Randomisierung immer in der richtigen Reihenfolge bleiben..

**MIDI-Kanal Unisono:** MIDI-Ereignisse von einem Kanal auf einen anderen duplizieren.

**MIDI-Strum:** Ein MIDI-Arpeggio-Effekt, der das Anschlagen eines Saiteninstruments (z. B. einer Gitarre) simulieren soll. Ein Akkord wird „gesammelt“ und die einzelnen Noten des Akkords werden zeitlich versetzt wiedergegeben. Der „Note Collect Timeout“ ermöglicht es, den Effekt live mit einem midi-keyboard zu spielen; er gleicht aus, dass ein Mensch die Tasten nicht exakt gleichzeitig drückt. Wird der Effekt mit einem Sequenzer verwendet, der Akkorde mit allen Note-on-Nachrichten exakt gleichzeitig senden kann, sollte er auf null gesetzt werden..

**MIDI-Chromatische Transposition:** Chromatische Transposition von MIDI-Noten und Key-Pressure. Wenn ein Umkehrpunkt festgelegt ist, wird die Skala vor der Transposition an diesem Punkt gespiegelt. Noten, die außerhalb des gültigen Bereichs 0..127 liegen, werden verworfen..
MIDI Monophones Legato	Halte eine Note, bis die nächste Note eintrifft. -- Spiele dieselbe Note erneut, um sie auszuschalten..

**MIDI Active Sensing entfernen:** Filter zum Blockieren aller Active Sensing-Ereignisse. Active Sensing-Nachrichten sind optionale MIDI-Nachrichten und dafür vorgesehen, wiederholt gesendet zu werden, um einem Empfänger mitzuteilen, dass eine Verbindung aktiv ist, können jedoch den MIDI-Kanal überfrachten oder versehentlich aufgezeichnet werden, wenn rohe MIDI-Daten auf die Festplatte geschrieben werden.

**MIDI-Duplikatblocker:** MIDI-Duplikatblocker. Filtert sich überlappende Note-on/off- und doppelte Nachrichten heraus.

**Note2CC:** MIDI-Note-on-Nachrichten in Control-Change-Nachrichten umwandeln.

**MIDI-Notenumschaltung:** Noten umschalten: Spiele eine Note, um sie einzuschalten, spiele sie erneut, um sie auszuschalten..

**MIDI N-Tap Delay:** Dieser Effekt wiederholt Noten N-mal. Dabei ist N entweder eine feste Zahl oder unbegrenzt, solange eine bestimmte Taste gedrückt wird. Die Variablen BPM und Delay-Zeit ermöglichen Tempo-Ramps. Bei jeder Wiederholung wird die angegebene Velocity-Anpassung addiert oder subtrahiert, das Ergebnis wird auf den Bereich von 1 bis 127 begrenzt.

**MIDI Thru:** MIDI All pass. Dieses Plugin hat keine Wirkung und ist als Beispiel gedacht.

**MIDI-Quantisierung:** Live-Event-Quantisierung. Dieser Filter richtet eingehende MIDI-Events an einem festen Zeitraster aus. Da der Effekt auf einem Live-Stream arbeitet, führt er zu Latenz: Events werden bis zum nächsten 'tick' verzögert. Wenn der Plugin-Host BBT-Informationen bereitstellt, werden die Events an der Clock des Hosts ausgerichtet, andernfalls läuft der Effekt mit seiner eigenen Zeit..

**MIDI-Velocity-Randomisierung:** Velocity von MIDI-Noten randomisieren (sowohl note on als auch note off).

**Skalierungs-CC-Wert:** Den Wert (Datenbyte) einer MIDI-Control-Change-Nachricht ändern.

**MIDI Sostenuto:** Dieser Filter verzögert Note-off-Nachrichten um eine bestimmte Zeit und ahmt so ein Sostenuto-Pedal eines Klaviers nach. Wenn das Pedal losgelassen wird, werden noch in der Warteschlange befindliche Note-off-Nachrichten sofort gesendet. Die Verzögerungszeit kann dynamisch geändert werden, Änderungen wirken sich auf Note-off-Nachrichten aus, die sich noch in der Warteschlange befinden.

**MIDI Velocity-Range-Filter:** Filtere MIDI-Note-on-Events nach Velocity. Note-on-Events außerhalb des zulässigen Bereichs werden verworfen. Wird ein Note-off für eine Note empfangen, die zuvor gefiltert wurde, wird es ebenfalls nicht weitergeleitet. Wenn sich der zulässige Bereich ändert, werden Note-off-Events an aktuell aktive Noten gesendet, die dadurch außerhalb des gültigen Bereichs liegen.

**MIDI Velocity-Anpassung:** Ändere die Velocity von Notenereignissen mit separaten Reglern für Note-on und Note-off. Der Eingabebereich 1 - 127 wird auf den Bereich zwischen Min und Max abgebildet. Wenn Min größer als Max ist, wird der Bereich umgekehrt. Der Wert offsets wird nach der Abbildung des Min/Max-Bereichs zur Velocity des Ereignisses addiert..
