# Face-recognition-led

**Ursprünglilche Idee:**
Mit einem ESP 32 Cam, wollen wir einen Servo-Motor ansteuern, der bei verschiedenen Gesichtern, die durch die Cam live aufgenommen werden können, das jeweilige Harry Potter-Haus ausgibt. Hier war die Idee, das wie auf einer Art "Glücksscheibe", die Spitze des Servo-Motors hinzeigt. 

**Problem:**
Die Servo-Motoren (die wir besitzen), sowie die dazugehörigen Libaries, waren nicht mit dem ESP 32 und der Cam kompatibel, was immer wieder zu Abstürzen des ESPs oder der IDE führte.
Daraufhin überlegten wir uns eine Alternative und haben eine RGB-LED genutzt, um verschiedene Farben als Indikator für die Häuser zu nutzen.

**Definition der Farben**
Gryffindor = rot
Hufflepuff = grün
Ravenclaw  = pink
Slytherin = blau
