# Arbeits-Log 2D-Spiel

### 14.01
Konstantin hat Tilemaps als Map Vorlage und 2dgame Packages für unser Spiel gedownloaded z.B. TextMeshpro für das bessere Bearbeiten von Texten im Spiel.
Cyrus hat sich damit außeinandergesetzt ein Main Menu und ein Pause Menu zu erstellen. Dafür wird ein Canvas with panel als Hintergrund verwendet. Und Buttons eingefügt mit welche man in Zukunft auch das Spiel starten, laden und verlassen soll, sowie Einstellungen für z.B. die Lautstärke. Sozusagen wurde ein Plan dafür erstellt und sich mit Unity ein wenig vertraut gemacht.

Start Menu
- Start New Game
- Load Game
- Options
- Quit

Pause Menu
- Resume
- Options
- Back to Title


https://www.youtube.com/watch?v=zc8ac_qUXQY 
https://www.youtube.com/watch?v=JivuXdrIHK0
https://goo.gl/YdQ3MA

### 15.01
Heute hat sich Cyrus sich einen Plan für ein Save & Loading System erstellt, sowie ein Layout für die Optionen erstellt und hat C# Tutorial Packages von Unity gedownloaded.
Konstantin hat sich währenddessen um die Bewegung eines Players gekümmert und hat Micosoft Visual Studio fürs programmieren mit C# installiert.. (Gehen, laufen, springen)

https://www.youtube.com/watch?v=XOjd_qU2Ido
https://unity3d.com/de/2d/solution-guide

### 16.01
Heute haben wir versucht unsere tilemaps in unity einer tile palett hinzuzufühen, jedoch hatten wir Probleme bei der Größen formatierung.
Dabei spielt die Einstellung Pixels per Unit für die Tilemaps eine große Rolle, um diese gut zu formatieren.
Jedoch war das schwerer richtig einzustellen als gedacht.

https://www.youtube.com/watch?v=cR8jP8OGbhM
https://www.youtube.com/watch?v=WFO1GUKYARQ
http://devassets.com/assets/2d-mega-pack/
https://www.youtube.com/watch?list=PLPV2KyIb3jR42oVBU6K2DIL6Y22Ry9J1c&v=UbPiCgCkHTE
https://www.youtube.com/playlist?list=PLPV2KyIb3jR42oVBU6K2DIL6Y22Ry9J1c
https://learn.unity.com/tutorial/2d-platformer-challenge-paint-your-level?projectId=5c8838feedbc2a0ee1e7e030#5c8932f9edbc2a1410354fda
https://learn.unity.com/tutorial/platformer-mod-custom-triggers?projectId=5c8838feedbc2a0ee1e7e030#5d5af9b9edbc2a002489c903
https://learn.unity.com/project/2d-platformer-template
https://www.youtube.com/watch?v=0vtAoFaM43E
https://unity3d.com/de/learning-c-sharp-in-unity-for-beginners
https://learn.unity.com/tutorial/coding-in-unity-for-the-absolute-beginner#5cf19e6dedbc2a38d6e996c2


### 22.01
Heute ist uns gelungen eine vorläufige Tilemap zu erstellen. Generell haben wir uns vorgenommen erst uns auf die Programmierung des Spiels zu konzentrieren, und Grafische Elemente erst später zu bearbeiten. Cyrus hat sich damit beschäftigtn eine kleine Grundebene zu erstellen um den Player auf dieser Ebene zu bewegen.Währenddessen hat Konstantin sich verschiedene Wege angeschaut die Programmierung für die Bewegung zu implementieren.

### 23.01 
Heute hat Cyrus vorübergehend eine rote Kugel dem Spiel eingefügt, welche den Player darstellen soll. Zudem hat sich Cyrus mit Gameobject Eigenschaften befasst bzw. welche Funktionen benötigt werden um den Spieler zu bewegen.

### 28.01
Heute war Konstantin krank, weil direkt am Unity Dokument nicht weiter gearbeitet werden konnte hat Cyrus sich über einige Funktionen in Unity informiert

### 04.02
Heute hat Konstantin es geschafft ein C# Script dem Spiel   einzufügen, jedoch waren Teile des Scripts fehlerhaft. Cyrus hat in der Zeit am Arbeitslog gearbeitet.

### 05.02
Heute hat Cyrus die Grafischen Elemente für das Main Menu erstellt, Konstantin hat währenddessen ein Unity Project zum Lernen von C# für 2d Spiele gedownloaded.
![Main Menu](/images/MainMenu1.0.JPG)

### 06.02 
Heute hat sich Cyrus das Unity Package CineMachine angeschaut, welches sich sehr eignet für das Erstellen einer Spiel Kamera. Z.B kann man leich einstellen, dass die Kamera der Bewegung des Players folgt ohne dafür einen Script zu erstellen. Konstantin hat angefangen sich mit der Bewegung des Players auseinander zu setzen. 

### 12.02
Heute hat Cyrus sich über Speichermöglichkeiten von Spielständen informiert. Dabei haben wir vor die sämtlichen PlayerData Informationen/Variablen als Binary-Files einspeichern und auszulesen. Heute hat Konstantin sein geschriebenes C# Script auf Fehler überprüft.

### 13.02 
Heute haben wir uns feste Gedanken über die Entwicklung des Spiels gemacht. Es soll ein Single Player - Open World - 2D Spiel. Dabei wird ein World Generator die Herausforderung des Projekts. Ein bekannter Triple A Titel aus diesem Genre ist zB. Terraria. Konstantin hat am Blog geschrieben. Konstantin hat sich mit weiter mit der Problembehebung des fehlerfreien scripts beschäftigt. Dabei fand er heraus, dass das script falsch zum player zugeordnet war. Cyrus hat es geschafft von Assets Store CineMachine zu downloaden.

### 14.02
Heute ist uns aufgefallen das viele Bearbeitungen in dem Arbeitsblog nicht übernommen wurden somit 45min Arbeit verloren gegangen ist.
Das konnte dank Konstantins Gedächniss schnell wieder aufgeschrieben werden. Jetzt geht es weiter mit dem programmieren. Cyrus hat weiter am Abspeicherungssystem gearbeitet. 

### 19.02
Heute war Konstantin krank, Cyrus hat sich in der Zeit damit befasst einen 2D Terrain Generator zu erstellen. Als nächstes erstellen wir einfarbige Tiles für die Varietäten von Blöcken, welche generiert werden sollen. 

### 20.02 
Heute war Konstantin wieder krank, doch ich habe mir den Laptop besorgt um weiterzuarbeiten. Momentan stehe ich vor der Herausforderung einen Procedural 2d Terrain Generator zu erstellen. Damit lässt sich eine Spielwelt komplett künstlich erstellen. 

### 06.03
Heute haben wir gemeinsam versucht einen Script für die Bewegung fertig zustellen. Das bisherige Problem war das Unity das Spiel nicht starten ließ, aufgrund von Comile errors. Bestimmte Packages meldeten uns mehrmals Fehlermeldungen und wir konnten nicht überprüfen ob der Script funktioniert. Zudem wurde unser rote Ball nicht in der Vorgerenderten Kamera angezeigt. Das bedeutet das die Einstellung für die SortingLayer nicht richtig waren. Zusätzlich war unsere Kamera komplett verbuggt.

### 11.03
Heute ist Cyrus krank und deshlab schreibt Konstantin den Arbeitsblog weiter. 
