# Einstieg in die Quantenprogrammierung mittels Microsoft Quantum Development Kit (QDK)

Die folgenden Notebooks wurde im Rahmen der Vorlesung "Quantum Computing and Information  (QCI) des Masters Studiengangs Informatik an der Hochschule Kaiserslautern - University of Applied Sciences, Campus Zweibrücken erstellt.<br>
<!--
<img src="https://user-images.githubusercontent.com/24352711/60571868-a1554d00-9d74-11e9-9756-7f3cd473cdfe.png" alt="hs logo" width="30%"/><br>
-->
https://www.hs-kl.de/

## QDK

Das Quantum Development Kit (QDK) ermöglicht das Entwickeln von Quanten Algorithmen sowie Programmen. Die genutzte Programmiersprache Q# ist eine skalierbare, domänenspezifische Programmiersprache mit mehreren Paradigmen für das Programmieren von Quantum Algorithmen.

## Voraussetzungen

Hier sind die Schritte aufgeführt, die Sie zum Erstellen eigener Q#-Notebooks ausführen müssen. IQ# ist eine hauptsächlich von Jupyter und Python genutzte Erweiterung für das .NET Core SDK, welche die Kernfunktionen für das Kompilieren und Simulieren von Q#-Vorgängen bereitstellt.

* [Python 3.6](https://www.python.org/downloads/) oder höher 
* [Jupyter Notebook](https://jupyter.org/install)
* [.NET Core SDK](https://dotnet.microsoft.com/download) 3.0 oder höher

Bevor Q#-Code ausgeführt werden kann, muss das Jupyter Notebook zunächst eine passende Umgebung bereitstellen. Hierzu muss nach Installation des .NET Core SDKs die Eingabeaufforderung geöffnet werden und die folgende Befehle ausgeführt werden. Achtung: Nach jeder Ausführung, muss die Eingabeaufforderung geschlossen und neu gestartet werden, damit die Änderungen am System erkannt werden!

* dotnet tool install -g Microsoft.Quantum.IQSharp
* dotnet iqsharp install

## Notebooks
#### Intro_QDK.ipynb
Dieses Notebook befasst sich mit den grundlegenden Konzepten, die zum Erstellen von Quantenprogrammen in Q# benötigt werden.

#### Deutsch-Jozsa-Algorithmus.ipynb
Dieses Notebook befasst sich mit einer Umsetzung des Deutsch-Jozsa Algorithmus in der Programmiersprache Q#.

## Versionierung
* 1.0: Veröffentlichung

## Author
   Eric Gustav Werner – [GitHub Profil](https://github.com/Gruschtel)
