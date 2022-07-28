# Media Control Box
## Idee
Ich möchte physische Kontrolle über einige Smarthome Geräte wie Lautsprecher oder Google Home Minis haben. Dazu greife ich auf ESPhome und NodeMCU Microcontroller zurück!

Alles weitere erkläre ich in diesem Video: 

## Umsetzung
### Hardware
In einer Projektbox sind ein NodeMCU ein Kippschalter und ein Rotary Encoder (KY-040) untergebracht. Die Anschlüsse können der YAML Datei entnommen oder von euch geändert werden.
### Software
In der einen beigefügten YAML Datei ist die config des NodeMCUs enthalten. Dazu gehören auch die Programmierung des Rotary Encoders und die Integration des Kippschalters. 
In der Automation innerhalb von Home Assistant wird der Schalter mit der Steckdose der Lautsprecher "verbunden".
Danke an Adamaze für die Inspiration! https://github.com/adamaze/esphome_volume_knob


Bei Fragen schreibt mir gerne unter dem Youtube Video!
