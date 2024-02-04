# 14570-Uhrzeit-Trigger

## Beschreibung 

Der Baustein triggert zu bis zu zwei Uhrzeiten.

## Eingänge

| Nr. | Name              | Initialisierung   | Beschreibung                                                                         |
|-----|-------------------|-------------------|--------------------------------------------------------------------------------------|
| 1   | Start / Stop      | 0                 | Bei dem Wert 1 wird der Baustein gestartet. Bei dem Wert 0 wird der Baustein beendet |
| 2   | Intervall         | 0                 | Intervall in Sekunden.                                                               |
| 3   | Uhrzeit 1         | 0                 | Uhrzeit 1 für Trigger (H:M)                                                          |
| 4   | Uhrzeit 2         | 0                 | Uhrzeit 2 für Trigger (H:M)                                                          |
## Ausgänge

| Nr.  | Name    | Initialisierung | Beschreibung                                                 |
|------|---------|-----------------|--------------------------------------------------------------|
| 1    | Trigger | 0               | Hier wird eine 1 gesendet bei Übereinstimmung von E3 oder E4 |


## Beispielwerte

| Eingang | Ausgang |
| --- | --- |
| - | - |


## Other

- Neuberechnug beim Start: Nein
- Baustein ist remanent: nein
- Interne Bezeichnung: 14497
- Kategorie: Datenaustausch

### Change Log

 - v0.1
   - Initial

   


## Requirements


## Licence

Copyright 2023

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
