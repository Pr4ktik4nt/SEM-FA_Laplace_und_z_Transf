# SEM-FA_Laplace_und_z_Transf
Seminar Fourier Analysis Laplace und Fourier Analysis

### Problem bei der Fouriertransformation erläutern
Die Fourier Transformation hat ein Problem:
![image](https://github.com/user-attachments/assets/2854ba17-a684-495f-9f8a-4608f6181980)
(1, S.878)
Und zwar wird bei den Grenzen Unendlich und -Unendlich nicht der Grenzwert Null erreicht. Löst man beispielsweise eine DGL bekommt man häufig Exponentialfunktionen enthaltene Lösungen.
z.B. schon bei ![image](https://github.com/user-attachments/assets/57ee235a-7281-40cd-bcc4-6a9eae3071e7)
(1, S.878)
Die Funktion strebt für die Grenzwerte gegen Unedlich:
![image](https://github.com/user-attachments/assets/ad6ea5a7-20dd-4535-adb4-86017fd0e846)
(1, S.879)

#### Wie wird es von Laplacetransformation gelöst?
Das Problem lässt sich mit Hilfe der Laplace Transformatione lösen.
Dafür braucht es die Erweiterung der Fourier Transformation um zwei Faktoren:
![image](https://github.com/user-attachments/assets/a3a74150-6fb6-4705-9315-0a6a3fa2bbbe)
(1, S.879)
(Warum kann man das machen? Wird die FUnktion so nicht zu einer völlig anderen???)

Problematisch ist hier, dass beide Faktoren für
![image](https://github.com/user-attachments/assets/1ed4a1f5-6838-41ef-8ab6-196ca046239b) 

schnell gegen Null streben, für 
![image](https://github.com/user-attachments/assets/90bec34d-d809-4902-9206-0c798f4ebbaa)

jedoch gegen Unenedlich. Deshalb muss die Bedingung 

![image](https://github.com/user-attachments/assets/8997c731-ad7a-4907-a08d-ea5b2bf603a2) 

gegeben sein. Da wir in der Praxis häufig DGLs mit der Lapplace Transformation lösen wollen und diese meist ein Anfangswertproblem darstellen, welches erst ab t=0 startet, ist diese Bedingung in vielen Anwendungsbeispielen gegeben.
Beispielsweise:

![image](https://github.com/user-attachments/assets/0b7bd428-6948-48ca-a016-dc717e50d65e)
(1, S.879)
Aufgrund dieser Bedingung kann man die untere Grenze zu Null setzen. Delta und jw sind zudem addiert als s definiert.

![image](https://github.com/user-attachments/assets/095c8dd2-b5fe-4f10-b174-1d1c79028d7d)
(1, S.879)


### Definition der Laplacetransformation und allgemeine Bezeichnung

"_Eine Funktion_ 
![image](https://github.com/user-attachments/assets/8626c418-a000-4d8d-bad6-55a081d1375c)

 _heißt genau dann Laplace-transformierbar, wenn das Integral_

![image](https://github.com/user-attachments/assets/e54f8f3a-2a78-4727-8871-6dbeeaac1ce8)

_für ein_ 

![image](https://github.com/user-attachments/assets/bd63eac6-67f3-467e-a57b-5ae946a5bb45)

_erklärt ist und konvergiert._

_Ist eine Funktion_ 
![image](https://github.com/user-attachments/assets/7ed7c39e-e8c8-4d1c-b326-818071c9f107)
_wieder eine Funktion definiert, die **Laplace-Transformierte**_ F von f. "


### allgemeine Korrespondenzen herleiten

![image](https://github.com/user-attachments/assets/7b0b61a0-c3e1-4064-83b6-3d93e6cb8170)
(Tabelle der allgemeinen Laplace Referenzen, 1, S.883)

### Rechenregeln der Laplacetransformation

#### Linearität
![image](https://github.com/user-attachments/assets/d2619c72-65c8-4d56-b769-ade7a47c07db)
Beispiel:
![image](https://github.com/user-attachments/assets/c11a3dd5-7c99-4aa3-9f26-93e9e04d70a2)
(1, S.883)

Der Faktor wird also vor die Transformierte gezogen.

#### Streckung

![image](https://github.com/user-attachments/assets/8c8b7a24-2995-4b92-9c37-1ffec6c46584)
Beispiel:
![image](https://github.com/user-attachments/assets/599e065e-868e-43c7-a7af-cd0357f821a3)
(1, S.884)
Der Faktor im Argument der zu transformierenden Funktion wird zum Faktor im Nenner der Transformierten.

#### Dämpfung

![image](https://github.com/user-attachments/assets/1c24ad53-ed3b-4866-a3b1-10422a968af4)
Beispiel:
![image](https://github.com/user-attachments/assets/b71db76d-4334-42fe-a38d-712a87b9feb4)
(1, S.884)
(???)

#### Ableitung

Sei f auf ![image](https://github.com/user-attachments/assets/36090da3-a06c-49d1-8268-5299238abd3d) mindestens differenzierbar, wobei die Ableitung f' auf jeden endlichen Intervall nur endlich viele Sprungstellen besitzt (also stückweise stetig ist). Alternativ kann f auch stetig differenzierbar auf ![image](https://github.com/user-attachments/assets/0a162cd6-860a-4e86-b518-b1a62e80cd53) sein, dann kann folgende Rechenregel angewendet werden:

![image](https://github.com/user-attachments/assets/b0d0ceca-dad2-442a-98d5-cd1b03a6e420)
Beispiel:
![image](https://github.com/user-attachments/assets/c28d881e-c6e9-4a48-91c1-3deb5a38cfcd)

Bei höheren Ableitungen muss iterativ vorgegangen werden, wobei die Anfangsbedingungen einbezogen werden und mit steigender Potenz von s der Grad der Ableitung fällt. 

![image](https://github.com/user-attachments/assets/aa6e3ac8-916e-48e8-b666-35ebee1a8140)
(1, S.884)

#### Stammfunktion

![image](https://github.com/user-attachments/assets/c90d69dd-bdcc-4990-8253-991a998d84c6)
Beispiel:
![image](https://github.com/user-attachments/assets/ecc26504-34ab-41e7-a78a-dea269a7fc90)

#### Faltung

![image](https://github.com/user-attachments/assets/fe1e8dcd-6196-4542-a9cf-97fbcb2b30f6)
Beispiel:
![image](https://github.com/user-attachments/assets/7e1b7042-1166-4765-afbe-2e9e4adb3580)

### 

### Anwendung: Lösen von DGLs

(Für die Informatiker:) Was sind Differentialgleichungen? Differentialgleichungen sind solche Gleichungen, die aus Ableitungen derselben Funktion mit verschieden hohem Rang bestehen.
Gegeben sein müssen dafür die Anfangsbedingungen bis zur Ableitung vor der mit dem höchsten Rang.
Veranschaulichen lässt sich das an einem allgemeinem Beispiel einer DGL mit der zweiten Ableitung als höchste Ableitung. 
![image](https://github.com/user-attachments/assets/2e095794-476c-4660-b1a6-e9b8922bec7c)
(1, S.886)
Nach Anwenden der Ableitungs- und Linearitätsregel erhält man die Laplace Transformierte. Auf die rechte Seite muss entsprechend die Korrespondenztabelle angewendet werden.
![image](https://github.com/user-attachments/assets/8a07e35d-8eee-412f-9f8d-6e23ffbd637f)

Durch Rücktransformation erhält man dann eine Lösung des Ursprungsproblems. Wenn man im Laplace-Bereich zwei Funktionen multipliziert, entspricht das im Zeitbereich einer Faltung dieser Funktionen. Man wendet dabei das so genannte Faltungstheorem an:
![image](https://github.com/user-attachments/assets/a13d322b-63bb-4eb9-99e1-af4ecbb7d816)
So ergibt sich die Lösung der Rücktransformation:
![image](https://github.com/user-attachments/assets/8ab4c2f2-1728-4f69-8142-f9988bf70b2c)
![image](https://github.com/user-attachments/assets/293eae9a-9a0e-4ba5-8012-507f1da40909)
(1, S.886)

Beispiel mit Zahlenwerten und Exponentialfunktion (Habe ein Beispiel aus dem Buch genommen. Vielleicht können wir hier eins aus Systemtheorie einfügen, sodass wir nicht bei allem auf Göbbis Buch zurückgreifen):

![image](https://github.com/user-attachments/assets/aa091d58-f0fb-4c22-a11c-75b89eed6104)

#### Unterschied Anwedung der Ableitungsregel auf Fouriertransformation vs Laplace Transformation

Die Fourier-Transformation unterscheidet sich in Bezug auf die Ableitungsregel von der Laplace-Transformation, da bei ihr keine Anfangsbedingungen berücksichtigt werden – was darauf zurückzuführen ist, dass über den gesamten Zahlenraum von −∞ bis ∞ integriert wird, statt wie bei der Laplace-Transformation ab null. Außerdem sind Funktionen mit exponentiellem Wachstum zwar Laplace-, aber nicht Fourier-transformierbar. Dadurch lassen sich bestimmte Lösungen mit der Fourier-Transformation nicht erfassen. Da exponentielle Funktionen jedoch häufig als Grundbausteine in Lösungen von Differenzialgleichungen auftreten, bietet die Laplace-Transformation hier einen klaren Vorteil. (1, S.891)

### Grenzwertsätze als Alternative zur Rücktransformation

Will man nur bestimmte Informationen aus einer Laplace-Transformationen ziehen, wie zum Beispiel den Anfangswert und den Endwert, kann man statt der Laplace Rücktransformation auch die Grenzwertsätze auf die Laplace Transformierte anweden:

![image](https://github.com/user-attachments/assets/13393426-abe1-43c6-a00c-a8e651218e29)
![image](https://github.com/user-attachments/assets/b5bb9594-90a0-49e0-a882-9fc1abcb93c2)
(1, S.892)

### In der Systemtheorie: 
Bsp.: Verknüpfung von Übertragungssystemen

### Sätze: Anfangswertsatz, Endwertsatz

### Quellen

Goebbels und Ritter, Mathematik verstehen und anwenden [1]


