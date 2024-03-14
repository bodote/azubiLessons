# Vorstellung

- mich
- Azubis, jeder soll kurz auf bisherige Programmiererfahrung eingehen.

# TDD

## WARUM?

### Warum Testautomatisierung?

- je früher Bugs erkannt werden desto billiger zu fixen
- Code ist erweiterbar ohne Angst haben zu müssen bisherige Funktionalität zu zerstören
- kann der Architektur helfen
- ist besser und effizienter als Test - Last (wenn mans richtig anwendet)

## TDD als spezielle Form der Testautomatisierung

- TDD = Test First, dann erst Implementierung

### Warum TDD?

- von offensichtlichen nach weniger offensichtlich sortiert:
- Test müssen eh geschrieben werden
- Psychologische Faktoren : Testerstellung wird nicht auf später verschoben
- bessere Codequalität , weil Anwendungscode gleich leicht testbar geschrieben ist und nicht noch umgebaut werden muss

### Warum macht das nicht jeder ?

#### Pitfalls

es gibt einige Fallen in die mal läuft, wenn man frisch vom TDD-Tutorial, TDD in größeren Projekten anwenden will. z.B. [An Ultimate Guide To BDD(lass dich nicht vom Titel verwirren)](https://youtu.be/gXh0iUt4TXA?si=xDReoNnkctGPSaXZ), [TDD Revisited - Ian Cooper - NDC Porto 2023](https://youtu.be/IN9lftH0cJc?si=Af_9KUvlnCtNRjfL) oder 
[When Test Driven Development Goes Wrong](https://youtu.be/UWtEVKVPBQ0?si=CpmqJw6cn62mCXkM)

#### Steilere Lernkurfe

- statt "nur" die Anforderungen ("requirements" oder "specification") zu erstellen muss ich zusätzlich:
- wissen wir man Tests schreibt (also Testframeworks (z.B. Junit5, oder spring-boots @SpringBootTest oder @WebMVCTest) kennen)
- UND ich muss mich daran gewöhnen bei neuen Anforderungen zuerst über das Konzept/Design der Tests nachzudenken, wobei die zu Testende Funktion/Classe/Modul zunächst als "BlackBox" mental gesehen wird
- ich hinterfrage also gegenüber dem PO zuerst die Testbarkeit und nicht die Implementierbarkeit
- während du lern, gibt es auch Phasen in denen sich TDD "langsame" anfühlt als nicht-TDD, aber lass sich davon nicht ermutigen und versuche TDD-Fallen zu vermeiden und deinen persöntlichen Entwicklungsprozess zu continuierlich zu Verbessern.

## Der Weg ist das Ziel

TDD lernst du nicht in ein paar Wochen , das bemißt sich eher in Jahren und auf dem Weg erwarten dich viele sehr interessante Erkenntnisse, aber auch der eine oder andere Stolperstein, der dich hin und wieder zweifeln lässt.

## Azubi Feedback

Was ist eure Meinung? Was erwartet Ihr von diesem Fachunterricht?

Wenn jemand Vorbehalte (um nicht zu sagen Vorurteile) gegenüber TDD hat: was müsste passieren , damit du deine Meinung änderst ?
