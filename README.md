# Face-recognition-led

**Ursprünglilche Idee** <br>
Mit einem ESP 32 Cam, wollen wir einen Servo-Motor ansteuern, der bei verschiedenen Gesichtern, die durch die Cam live aufgenommen werden können, das jeweilige Harry Potter-Haus ausgibt. Hier war die Idee, das wie auf einer Art "Glücksscheibe", die Spitze des Servo-Motors hinzeigt. 
<br>
<br>
**Problem** <br>
Die Servo-Motoren (die wir besitzen), sowie die dazugehörigen Libaries, waren nicht mit dem ESP 32 und der Cam kompatibel, was immer wieder zu Abstürzen des ESPs oder der IDE führte.
Daraufhin überlegten wir uns eine Alternative und haben eine RGB-LED genutzt, um verschiedene Farben als Indikator für die Häuser zu nutzen.
<br>
<br>
**Anleitung**
1. Öffne den Sketch in der Arduino IDE und gib deinen individuellen WLAN-Namen und das dazugehörige Passwort ein.
2. Falls du später in Teachable Machine eigene Klassen benennen möchtest, solltest du die Klassen im Sketch noch umbenennen.
3. Trenne den ESP von der ESP Cam und verbinde dann durch Jumperkabel die RGB-LED und die Cam mit dem ESP 32.
4. Lade den Sketch auf den ESP hoch (nachdem du den richtigen Port und das richtige Board (AI Thinker ESP32-Cam) ausgewählt hast).
5. Lege in Teachable Machine ein Projekt mit 2 Klassen an. (Die Namen der Klassen sollten mit den Namen im Sketch übereinstimmen)
6. Exportiere dein Projekt, sodass du einen Link erhälst (Modell exportieren und hochladen für Tensorflow.js).
7. Link kopieren und im Browser einfügen. Den Link zum richtigen Port findest du im Seriellen Monitor, sobald der Sketch auf den ESP hochgeladen wurde.
8. Probier es aus! :) 
<br>

**Definition der Farben**
<br>Gryffindor = rot
<br>Hufflepuff = grün
<br>Ravenclaw  = pink
<br>Slytherin = blau


