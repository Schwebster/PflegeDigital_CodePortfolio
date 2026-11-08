# Pflege-Digital

**C#-Codeportfolio einer interaktiven Unity-Anwendung zur Darstellung von Pflegeabläufen.**

Die Anwendung bildet Arbeitsschritte über interaktive Objekte, festgelegte Abläufe und Hinweise in der Benutzeroberfläche ab. Dieser Auszug zeigt die von mir entwickelte Programmierung des Projekts.

## Mein Beitrag

Ich habe den projektspezifischen C#-Code selbst entwickelt. Dazu gehören die Verwaltung von Arbeitsabläufen, die Interaktion mit Objekten, die Spielersteuerung und die Benutzeroberfläche. Die visuellen Assets des ursprünglichen Projekts stammen aus anderen Quellen und sind in diesem Codeportfolio ausgelassen.

## Technische Schwerpunkte

- **Ablaufsteuerung** mit definierten Arbeitssequenzen, benötigten Objekten und Objektpositionen.
- **Objektinteraktion** über Raycasts sowie Klassen für verwendbare Gegenstände und interaktive Elemente wie Bett und Türen.
- **Spielersteuerung** für Bewegung, Blickrichtung und Interaktion.
- **Benutzeroberfläche** mit Menüs, Arbeitsschritthinweisen, Fehleranzeige und Tooltips.
- **Lokalisierung** von Oberflächentexten.
- **Testcode** für Arbeitssequenzen und Spielerfunktionen mit Unity Test Framework, NUnit und NSubstitute.

## Einstieg in den Code

- [Arbeitssequenzen und ihre Initialisierung](Assets/Scripts/WorksequenceClasses)
- [Objektmodell und Interaktionen](Assets/Scripts/ObjectClasses)
- [Spielersteuerung](Assets/Scripts/PlayerClasses)
- [Oberfläche und Lokalisierung](Assets/Scripts/Canvas)
- [EditMode-Tests](Assets/Tests/EditMode)
- [PlayMode-Tests](Assets/Tests/PlayMode)

## Umfang dieses Portfolios

Enthalten sind 46 C#-Dateien aus den Ordnern Assets/Scripts und Assets/Tests, ergänzt um Unity-Metadaten und Assembly-Definitionen. Der Auszug hat keine übernommene Git-Versionsgeschichte.

Für eine ausführbare Unity-Anwendung werden zusätzlich die ursprünglichen Szenen, Modelle, Texturen, Animationen, Medien und Abhängigkeiten benötigt. Diese Kopie dient der Codeeinsicht. Auch die enthaltenen Tests benötigen die zugehörige Unity-Projektumgebung und Testabhängigkeiten.
