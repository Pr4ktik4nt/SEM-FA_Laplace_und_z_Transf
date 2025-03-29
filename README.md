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

## Wie wird es von Laplacetransformation gelöst?
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
(Tabell der allgemeinen Laplace Referenzen, 1, S.883)

### Rechenregeln der Laplacetransformation

## Linearität
![image](https://github.com/user-attachments/assets/d2619c72-65c8-4d56-b769-ade7a47c07db)
Beispiel:
![image](https://github.com/user-attachments/assets/c11a3dd5-7c99-4aa3-9f26-93e9e04d70a2)
(1, S.883)

Der Faktor wird also vor die Transformierte gezogen.

## Streckung

![image](https://github.com/user-attachments/assets/8c8b7a24-2995-4b92-9c37-1ffec6c46584)
Beispiel:
![image](https://github.com/user-attachments/assets/599e065e-868e-43c7-a7af-cd0357f821a3)
(1, S.884)
Der Faktor im Argument der zu transformierenden Funktion wird zum Faktor im Nenner der Transformierten.

## Dämpfung

![image](https://github.com/user-attachments/assets/1c24ad53-ed3b-4866-a3b1-10422a968af4)
Beispiel:
![image](https://github.com/user-attachments/assets/b71db76d-4334-42fe-a38d-712a87b9feb4)
(1, S.884)
(???)



### 

### Anwendung: Lösen von DGLs

### In der Systemtheorie: 
Bsp.: Verknüpfung von Übertragungssystemen

### Sätze: Anfangswertsatz, Endwertsatz

### Quellen

Goebbels und Ritter, Mathematik verstehen und anwenden [1]


