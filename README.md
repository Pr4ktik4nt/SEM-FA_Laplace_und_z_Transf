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

-> Wie wird es von Laplacetransformation gelöst?
Das Problem lässt sich mit Hilfe der Laplace Transformatione lösen.
Dafür braucht es die Erweiterung der Fourier Transformation um zwei Faktoren:
![image](https://github.com/user-attachments/assets/a3a74150-6fb6-4705-9315-0a6a3fa2bbbe)
(1, S.879)

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

"_Eine Funktion_ \( f : [0, \infty[ \to \mathbb{C} \) _heißt genau dann Laplace-transformierbar, wenn das Integral_

\[
F(s) := \mathcal{L}f(s) := \int_0^{\infty} f(t)\exp(-st)\,dt 
= \lim_{u \to \infty} \int_0^u f(t)\exp(-st)\,dt
\]

_für ein_ \( s \in \mathbb{C} \) _erklärt ist und konvergiert._

_Ist eine Funktion_ \( f \) _Laplace-transformierbar, dann ist über_ \( F := \mathcal{L}f \) _wieder eine Funktion definiert, die **Laplace-Transformierte**_ \( F \) _von_ \( f \)_._ "


### allgemeine Korrespondenzen herleiten

### Rechenregeln der Laplacetransformation

### 

### Anwendung: Lösen von DGLs

### Quellen

Goebbels und Ritter, Mathematik verstehen und anwenden [1]

### In der Systemtheorie: 
Bsp.: Verknüpfung von Übertragungssystemen

### Sätze: Anfangswertsatz, Endwertsatz



