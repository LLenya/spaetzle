---
title: "Codebuch"
output: html_document
author: "Lenya Trautmann lt043"
---

## Inhalt
- Edgelist.csv (Edgelist)
- Nodelist.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

Bitte erstellen Sie ein \*two-mode Netzwerk\* (Mitgliedschaft in

Organisationen). Deshalb benötigen Sie das Node-Attribut type, da es um

Personen und Organisationen geht, codiert als 0 und 1.

\*Grundregeln\*: Keine Sonderzeichen, keine Leerzeichen, jede Beziehung in

maximal eine Zeile. IDs aus Edge- und Nodelist müssen identisch sein.

Folgende Variablen müssen erhoben werden:

# EDGE-Attribute

*id*  
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird

*from*  
definiert den Sender in gerichteten Netzwerken. Entspricht ID in der Nodelist. 

*to*
definiert den Empfänger in ungerichteten Netzwerken. Entspricht ID in der Nodelist. 

*relationship*  
definiert Verbindungen zwischen Politiker*innen und dem Organisationen, codiert nach:   
1 = Ministerium 

2 = politische Funktion (Parteien, Gremien)

3 = Ehrenamt (Mitgliedschaften in NGOs, Stiftungen, Gedenkstätten)

4 = Unternehmen & Aufsichtsräte

5 = Stipendien

6 = Berufstätigkeiten

7 = Studien- und längere Aufenthalte im In- und Ausland

*year*  
das Jahr der Verbindung

# NODE-Attribute  
  
\- *id*  
eindeutige Identifikation jedes einzelnen Knotens (vertex), der erfasst wird - identisch mit den IDs der Edge-List

\- *short_name*
Nachname der/des Politiker/in

\- *name* 
Vollständiger Name der/des Politkerin/Politikers

\- *sex*    
Geschlecht, numerische Ausprägung/Codierung: 
1 = weiblich/female
2 = männlich/male
  
\- *education*    
höchster Bildungsabschluss, numerische Ausprägung/Codierung: 
1 = Diplom
2 = Promotion
3 = Staatsexamen
4 = Magister

\- *position*   
jetzige Position, Codierung: 
1 = Staatssekretär_in
2 = Minister/in

\- *subject*    
Fachrichtung bei Studium/Promotion, Codierung: 
1 = Politik
2 = Rechtswissenschaften
3 = Sozial
4 = Wirtschaft
  
\- *party*    
Parteizugehörigkeit, Codierung: 
gruene = Gruene/Bündnis 90
fdp = FDP
spd = SPD 
  
\- *religion*    
Religion, Codierung:
1 = evangelisch
2 = katholisch  

\- *kids*  
Anzahl Kinder  

\- *twitter*  
Anzahl Twitter-Follower

\- *facebook*  
Anzahl Facebook-Follower

\- *instagram*  
Anzahl Instagram-Follower

\- *youtube* 
Anzahl Youtube-Abonnenten

\- *type* 
Art des Knoten, Codierung: 
0 = Person
1 = Organisation

##
