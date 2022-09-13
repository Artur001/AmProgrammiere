# Projekt-Dokumentation

 Artur Bytyqi

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|23.8.2022| 1.0   | Das Spiel ist erfolgreich |
|30.8.2022| 1.1   | Der Text wird "ausgeschrieben" und nicht alles auf einmal |

## 1 Informieren

### 1.1 Ihr Projekt

Mein Projekt ist ein Zahlenerratespiel.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    | Muss | Funktional | Als Spieler möchte ich wissen, ob die Zahl die ich eingegeben habe richtig oder falsch ist und ob es kleiner oder grösser ist |
| 2  | Muss  |Funktional| Als Spieler möchte, dass mir gesagt wird, wie oft ich geraten habe    |
| 3  | Muss  |Funktional| Als Spieler möchte ich die Auswahl haben, ob ich nochmal spielen will.   |
| 4  | Kann  |Funktional| Als Spieler möchte ich, dass ich nicht Zahlen über 100 schreiben kann, sonst soll ich verwarnt werden.   |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  | Programm gestartet und Zufallszahl wurde generiert |yo |Ich sege Zahl und du chunnsch mit Buechstabe... Probier nomal dumme siech|
| 1.2  |Programm gestartet und Zufallszahl wurde generiert              |71 |Nah zu gross |
| 1.3  |Programm gestartet und Zufallszahl wurde generiert              |71 |Nah zu chli |
| 2.1  |Programm gestartet und Zufallszahl wurde bereits gefunden              |Enter |Ja easy nach (Anzahl Rate) mal hesch errate |
| 2.2  |Programm gestartet und Zufallszahl wurde beim ersten Versuch gefunden              |Enter |WASSSSS???? FIRST TRY???? |
| 3.1  |Programm gestartet und Zufallszahl wurde bereits gefunden              |Enter |Wotsch nomal? schrib entweder Y (ja) oder N (nah) |
| 4.1  |Programm gestartet und Zufallszahl wurde generiert              |2134 |KOLLEG ICH SEGE VO 1-100 AMIGO. KOMPLETT LOSTE SIECH |



### 1.4 Diagramme

*Ich habe einen Mac und daher funktionert PAP nicht bei mir.*

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |  23.8.2022     |  Ich      | Realisierung eines Projektdokumentes    | 2 * 45  |
| 1.B  | 30.8.2022 | Ich     | Realisierung wird begonnen   | 4 * 45 |
| 1.C  | 6.9.2022 | Ich     | Realisierung wird fortgesetzt, beendet und getestet.   | 3 * 45  |
| 1.D  | 13.9.2022 | Ich     | Project wird abgeschlossen und abgegeben   |2 * 45 |

Total: **11 * 45**


## 3 Entscheiden

Ich entschied mich für wie gross die Zahl ist zwischen 1-100, weil grössere Zahlen machen keinen Sinn. Welcher Mensch geht zu einem und fragt: "Sag mir eine Zahl von 1 bis 1000. Wenn du richtig ratest, bekommst du etwas." Wie oft man geratet hat, ist für mich auch lustig und man kann z.B. zeigen, dass man nur einmal geratet hat und es richtig war. Man bekommt sogar eine Nachricht, wie das Programm überzeugt ist. Das wollte ich auch. Sehr interessant war für mich, wie man die Funktion macht, dass man nochmals spielen kann. Diese Funktion brauchte am meisten Zeit für mich, weil ich es einfach nicht verstanden habe. Ich entschied mich auch noch, dass wenn man Zahlen über die Range schreibt, dass man erst als dumm beleidigt wird und dann verwarnt wird. Die Verwarnung ist, wenn man beim zweiten Mal wieder eine Zahl über 100 schreibt, dass das Programm sagt, dass es "kein Bock" mehr hat.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |    23.8.2022   | Artur       | 2 * 45              |   2 * 45                |
| 1.B  | 30.8.2022      | Artur          | 4 * 45     | 5 * 45    |
| 1.C  | 6.9.2022  |  Artur    |    3 * 45   |  2 * 45    |
| 1.D  | 13.9.2022  |  Artur    | 2 * 45  | 2 * 45 |


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |13.9.2022| Zahl wird generiert |Artur |
| 1.2  | 13.9.2022    |Programm sagt ob Zahl höher oder tiefer ist |Artur |


### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    | Jonah hat einen kleinen Bug gefunden; wenn man eine Zahl über 100 eingibt, dass das Programm beim zweiten Male aufhören soll|2 x eine Zahl über 100 |"weisch was, ich han eif kb meh bro.."|schon beim ersten Mal eine Zahl über 100 schreiben kommt diese Nachricht |


## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
