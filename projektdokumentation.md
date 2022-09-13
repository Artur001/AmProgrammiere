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
| 1.D  | 13.9.2022 | Ich     | Project wird abgeschlossen und abgegeben   |3 * 45 |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |        |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
