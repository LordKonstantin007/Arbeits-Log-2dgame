# Arbeits-Log 2D-Spiel

### 14.01
Konstantin hat Tilemaps als Map Vorlage und 2dgame Packages für unser Spiel gedownloaded z.B. TextMeshpro für das bessere Bearbeiten von Texten im Spiel.
Cyrus hat sich damit außeinandergesetzt ein Main Menu und ein Pause Menu zu erstellen. Dafür wird ein Canvas als Panel im Hintergrund verwendet und Buttons eingefügt mit welche man in Zukunft auch das Spiel starten, laden und verlassen soll.

### 15.01
Heute hat sich Cyrus sich einen Plan für ein Save & Loading System erstellt, sowie ein Layout für die Optionen erstellt und hat C# Tutorial Packages von Unity gedownloaded.
Konstantin hat sich währenddessen um die Bewegung eines Players gekümmert und hat Micosoft Visual Studio fürs programmieren mit C# installiert.. (Gehen, laufen, springen)

### 16.01
Heute haben wir versucht unsere tilemaps in unity einer tile palett hinzuzufühen, jedoch hatten wir Probleme bei der Größen formatierung.
Dabei spielt die Einstellung Pixels per Unit für die Tilemaps eine große Rolle, um diese gut zu formatieren.

### 22.01
Heute ist uns gelungen eine vorläufige Tilemap zu erstellen. Generell haben wir uns vorgenommen erst uns auf die Programmierung des Spiels zu konzentrieren, und Grafische Elemente erst später zu bearbeiten. Cyrus hat sich damit beschäftigtn eine kleine Grundebene zu erstellen um den Player auf dieser Ebene zu bewegen.Währenddessen hat Konstantin sich verschiedene Wege angeschaut die Programmierung für die Bewegung zu implementieren. Jedoch lies sich das Spiel nicht richtig ausführen.

### 23.01 
Heute hat Cyrus vorübergehend eine rote Kugel dem Spiel eingefügt, welche den Player darstellen soll. Zudem hat sich Cyrus mit Gameobject Eigenschaften befasst bzw. welche Komponenten benötigt werden um den Spieler zu bewegen. (Tile Renderer, Box Collider und Rigidbody.)

### 28.01
Heute war Konstantin krank, weil direkt am Unity Dokument nicht weiter gearbeitet werden konnte hat Cyrus sich über einige Funktionen in Unity informiert

### 04.02
Heute hat Konstantin es geschafft ein C# Script dem Spiel   einzufügen, jedoch waren Teile des Scripts fehlerhaft. Cyrus hat in der Zeit am Arbeitslog gearbeitet.

### 05.02
Heute hat Cyrus die Grafischen Elemente für das Main Menu erstellt, Konstantin hat währenddessen ein Unity Project zum Lernen von C# für 2d Spiele gedownloaded. Generell war es für uns schwierig dass zwei Leute gleichzeitig programmieren können. Weil Unity nur auf Konstantins Laptop ist und bei Cyrus Zuhause am PC.
![Main Menu](/images/MainMenu1.0.JPG)

### 06.02 
Heute hat sich Cyrus das Unity Package CineMachine angeschaut, welches sich sehr eignet für das Erstellen einer Spiel Kamera. Z.B kann man leich einstellen, dass die Kamera der Bewegung des Players folgt ohne dafür einen Script zu erstellen. Konstantin hat angefangen sich mit der Bewegung des Players auseinander zu setzen. 

### 12.02
Heute hat Cyrus sich über Speichermöglichkeiten von Spielständen informiert. Dabei haben wir vor die sämtlichen PlayerData Informationen/Variablen als Binary-Files einspeichern und auszulesen. Heute hat Konstantin einige Fehler im Player Movement Script behoben. Zum Beispiel da

### 13.02 
Heute haben wir uns feste Gedanken über die Entwicklung des Spiels gemacht. Es soll ein Single Player - Open World - 2D Spiel. Dabei wird ein World Generator die Herausforderung des Projekts. Ein bekannter Triple A Titel aus diesem Genre ist zB. Terraria. Konstantin hat am Blog geschrieben. Konstantin hat sich mit weiter mit der Problembehebung des fehlerfreien scripts beschäftigt. Dabei fand er heraus, dass das script falsch zum player zugeordnet war. Cyrus hat es geschafft von Assets Store CineMachine zu downloaden.

### 14.02
Heute ist uns aufgefallen das viele Bearbeitungen in dem Arbeitsblog nicht übernommen wurden somit 45min Arbeit verloren gegangen ist.
Das konnte dank Konstantins Gedächniss schnell wieder aufgeschrieben werden. Jetzt geht es weiter mit dem programmieren. Cyrus hat weiter am Abspeicherungssystem gearbeitet. 

### 19.02
Heute war Konstantin krank, Cyrus hat sich in der Zeit damit befasst einen 2D Terrain Generator zu erstellen. Dafür haben wir vorerst fremde Tiles, also nicht selbst erstellte Texturen für die Tiles/Prefaps verwendet.

### 20.02 
Heute war Konstantin wieder krank, doch ich habe mir den Laptop besorgt um weiterzuarbeiten. Momentan stehe ich vor der Herausforderung einen Procedural 2d Terrain Generator zu erstellen. Damit lässt sich eine Spielwelt komplett künstlich erstellen. 

### 06.03
Heute haben wir gemeinsam versucht einen Script für die Bewegung fertig zustellen. Das bisherige Problem war das Unity das Spiel nicht starten ließ, aufgrund von Comile errors. Bestimmte Packages meldeten uns mehrmals Fehlermeldungen und wir konnten nicht überprüfen ob der Script funktioniert. Zudem wurde unser rote Ball nicht in der Vorgerenderten Kamera angezeigt. Das bedeutet das die Einstellung für die SortingLayer nicht richtig waren. Zusätzlich war unsere Kamera komplett verbuggt.

### 11.03
Heute ist Cyrus krank und deshlab schreibt Konstantin den Arbeitsblog weiter.

### 13.03
Heute haben wir uns dazu entschlossen das Projekt neu zuerstellen in der neusten Unity Version, weil die von uns gedownloadedten Packages zu compiling errors bei der Ausführung des Spiels sorgten. Zudem ist uns aufgefallen, dass wir keine Tilemap benötigen wenn wir eine zufällig generierte Welt erstellen wollen. Stattdessen brauchen wir ein Script in welchem diese Generierung vorgegeben wird.

### 20.03
Heute hat Cyrus für das Spiel an einem World Generation Script gearbeitet. Dafür verwenden wir Perlin Noise:
![wg1](/images/wg1.PNG)

Außerdem haben wir immernoch das Problem, dass uns im Unity integrierten Spiel Window nichts angezeigt wird, was daraufhindeutet das die Camera falsch eingestellt ist.

### 21.03
Heute hat Cyrus den Script verändert. Es wurden neue Tiles dem Script hinzugefügt darunter Erze. Durch erstellte Parameter lassen sich folgende Dinge variieren: Spawnwahrscheinlichkeit der Erze, Terrainform, .... Außerdem haben wir haben uns dazu entschieden dies folgend zu machen:
Ein Scipt definiert die Größe eines Chunks und setzt weitere Chunks ans Ende eines Chunks. Für die Generierung der Chunks gibt es einen verknüptes Chunk Prefap welches durch den GeneratingChunk Script verbunden ist. Für die Auswahl eines Chunks ist einzufällig generierter Seed verantwortlich. Das bedeutet das jeder Seed von einem Random Number Generator (RNG) ausgewählt wird (eine Zahl zwischen 100000 und -100000) und durch das GeneratingChunks Script in eine feste Struktur umgewandelt wird.
![wg2](/images/wg2.PNG)
![wg3](/images/wg3.PNG)

### 22.03
Heute hat Cyrus die Chunks vergrößert und die Wahrscheinlichkeiten angepasst. Zudem haben wir einen Raum definiert in welchen Gold und Diamant Erze Spawnen können. Zudem wurde der Bug gefixxed, dass die Erze auch den jeweiligen Chunks angehören in welchen sie generiert werden.
Vorher:
![wg4](/images/wg4.PNG)
Nachher:
![wg5](/images/wg5.PNG)

### 23.03
Heute haben wir einen der Scripte von Konstantin ausprobiert, jedoch gibt es noch Schwierigkeiten mit:
- dem Springen
- der Bodenhaftung
- der Rotierung beim Springen
-> Hier Sichtbar: https://www.youtube.com/watch?v=905DFJR241g

### 24.03
Heute hat Cyrus ein Script geschrieben für eine Kamera welche den Spieler verfolgt. Dies funktioniert bisher nur für die X-Achse.

### 25.03
Heute wurde der Bugg gefixt und die Kamera folgt auch auf der Y-Achse.

### 26.03




