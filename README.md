# Dokumentation
# LA1100-1
Mein ersten Projekt

# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

Angel.Angelov

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|23.08.2022| 0.0.1   | Heute haben wir mit unseren Erseten Projekt angefangen und Dokumntation |
|30.08.2022| 0.0.2   |  |Heute habe ich die Grundprinzip von die Program gemacht und kann die jetzt benutzen|
|06.09.2022 | 0.0.3   |   Heute habe ich meine Program                                                          |

## 1 Informieren

### 1.1 Ihr Projekt

Mein ersten Auftrag ist eine Numberguesser Spiel zu programieren.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss            | Funktionel     | Als ein Benutzer dies Spiel möchte ich, dass die Programm ein zahl, generieren kann, damit die Spiel funktioniert.|
| 2    | Muss            | Funktioel      | Als Spieler möchte ich einer Zahl eingeben können, damit ich die zufälligen Zahle raten kann.|
| 3    | Muss            | Funktionel     | Als spieler möchte ich das die Program es mir sagt ob die Zahl grösser oder kleiner ist, damit ich die Zahl eraten kann|
| 4    | Muss            | Funktionel     | Als Speler möchte ich das die schon benutzten zahlen gezeigt werden, damit ich ich mich besser orintieren kann 
| 5    | Kann            | Funktionel     | Als ein Spiler möchte ich das, wenn ich die zahl earten habe, die Spiel nochmal speieln kann|

✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Apk starten zufällige Zahl generiren und Auf Eingabe warten|`""`|Geben sie bitte ein zahl ein| 
| 2.1  | Apk gestrtet zufällige Zahl generiert  |Zahlen| Die zufällige Zahl ist kleiner/Geben sie bitte ein zahl ein|
| 3.1  | Apk gestartet zufällige Zahl generiert    | Buchstaben eingegen |Geben sie bitte nur zahlen ein|
| 4.1  | Apk gestartet zufällige Zahl generiert |Zahlen | Glückwunsch sie haben es geschaft|
| 5.1  | Apk gestartet zufällige Zahl eratet    | `""` | Möchten sie nochmal spielen|
| 6.1  | Apk gestartet zufällige Zahl eratet | JA   | Apk wird nochmal gestartet |


✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme


![Screenshot 2022-08-23 110107](https://user-images.githubusercontent.com/110893454/186126467-b8c94fbd-9e9d-439d-9b19-84f94d31c0a0.png)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 23.08.2022| Ich          |    Informirung und Dokumentation  | 1 Arbeitspaket  |
| 2.A  | 30.08.2022| Ich         | Der Grundprinzip dür Programm programieren       | 3.Arbeitspakete |
| 3.A  | 6.09.2022          | Ich         | Zahlen läser programieren                        | 3.Arbeitspakete |
| 4.A  | 13.09.2022| Ich    |  Abschluss' testen und Abgabe | 2.Arbeitspakete|
Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 30.08.2022      |Informirung und Dokumentation|1.Arpeitspaket/45.min|    10.min               |
| 2.A  | 30.08.2022      |Der Grundprinzip dür Programm programieren | 3.Arbeitspakete |  3.Arbeitspakete  |
| 3.A  | 30.08.2022      |Zahlen läser programieren |3.Arbeitspakete|1.Arbeitspaket|

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 13.09.2022|Program wird gestartet, Zahl wird genereirt und wartet auf die eingabe, funktioniert| Angel Angelov       |
| 1.1  | 13.09.2022|Zahlen eingeben und es zeigt ob der Zahl grösser/kleiner ist, finktioniert         | Angel Angelov       |
| 1.1  | 13.09.2022|Buchstaben eingeben, program schmiert nicht ab und sgt das man keine Zahlen eingegeben hat     | Angel Angelov       |
| 1.1  | 13.09.2022|Zahl eraten, Program zeigt wie viele verscuche man gebraucht hat, funktioniert      | Angel Angelov       |
| 1.1  | 13.09.2022|Program fragt ob man noch mal spieleb will       | Angel Angelov       |
| 1.1  | 13.09.2022|Wenn man ja eingibt wiederhollt sich das Program und wenn nein ist es fertig     | Angel Angelov       |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I |Programm funktioniert und wartet auf eingabe    | " . und , "|   Geben s   |    eror    |


✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
