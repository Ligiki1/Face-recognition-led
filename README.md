# Zu welchem Harry Potter-Haus gehörst du?
**Ursprünglilche Idee** <br>
Mit einem ESP 32 Cam, wollten wir einen Servo-Motor ansteuern, der bei verschiedenen Gesichtern, die durch die Cam live aufgenommen werden können, das jeweilige Harry Potter-Haus ausgibt. Hier war die Idee, das wie auf einer Art "Glücksscheibe", die Spitze des Servo-Motors zeigt auf das jeweilige Haus. 
<br>
<br>
**Problem** <br>
Die Servo-Motoren (die wir besitzen), sowie die dazugehörigen notwendigen Libraries, sind nicht mit dem ESP32-Cam kompatibel, weshalb ein aufspielen nicht möglich war, zudem hat es immer wieder zu Abstürzen des ESPs oder der IDE geführt, bis der ESP unbrauchbar war.
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
9. Im Seriellen Monitor bekommst du dein entsprechendes Haus gesagt oder du schaust einfach auf die RGB-LED. Die Farbcodierung findest du weiter unten. :) 
<br>

**Definition der Farben**
<br>Gryffindor = rot
<br>Hufflepuff = gelb
<br>Ravenclaw  = blau
<br>Slytherin = grün


