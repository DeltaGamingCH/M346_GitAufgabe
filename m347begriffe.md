
Containerisierung -	Virtualisierung mit Hilfe von Containern. Dependencies, Frameworks etc. werden in Container verpackt. Sie kann in jeder beliebigen Umgebung ausgeführt werden. ~Voll Funktionsfähige Rechenumgebung
Image	- Schreibgeschützte Vorlage mit einem Speicherabbild eines Containers.
Layer - Teil eines Images. Enthält Befehl oder Datei, teil des Images. 
Container - Aktive Instanz eines Images.
Repository - Speicherstelle gleicher Images mit mehreren Tags/Verisonen.
Registry -	Verwaltet Repositories (DockerHub)
Dockerfile - Txt mit allen Befehlen, um ein Image zu erstellen.

Microservices
Eine Aufgabe, ein Container
Microservices sind die verschiedenen Container in einer Applikation, die genau einen Zuständigkeitsbereich haben. Als Beispiel, Eine API-Verbindung zur Datenbank, ein Container für das web Front-end, etc. 

Orchestrierung
	- Automatisierung von Deployment, Management, Skalierung, Vernetzung
	- Anstelle von einem Server, werden ganz viele Container gestartet. Funktioniert einer nicht, kann man ihn einfach ersetzen. 
