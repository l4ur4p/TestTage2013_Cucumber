[Stuttgarter Test Tage 2013](http://www.jugs.org/tt2013/)
=====================

�bung: Gurkensalat statt Spaghetticode
---------------------

### Vorbereitung
Clonen Sie das Github Repository `git@github.com:remast/TestTage2013_Cucumber.git`.
Dort finden Sie den Code und die Instruktionen zur �bung.

Alternativ k�nnen Sie das Repository auch als Zip-Archiv herunterladen:
https://github.com/remast/TestTage2013_Cucumber/zipball/master

�ffnen Sie nun Eclipse.

Importieren Sie dort das Projekt `cucumber.java-helloworld` aus dem Github Repository.
Gehen Sie dazu auf "File > Import > Existing Projects into Workspace" und w�hlen Sie 
dann das Verzeichnis `cucumber.java-helloworld` aus.

Nun sind Sie bereit mit der �bung zu beginnen.

### �bungen

#### Aufgabe 1: BDD Test ausf�hren
F�hren Sie die BDD Tests aus dem Beispielprojekt `cucumber.java-helloworld` aus. 
Die Konfiguration hierf�r ist bereits im Eclipse Projekt vorhanden.

F�hren Sie unter Eclipse die JUnit Launch Konfiguartion "RunCukesTest" aus.
Diese finden Sie im Men� "Run > RunCukesTest".

�ffnen Sie die *.feature Datei mit den Szenarien. Schauen Sie sich die verschiedenen Szenarien an. 

Verfolgen Sie die Ausf�hrung des Scenarios. Gehen Sie folgenden Fragen nach:
- Welche Klassen sind beteiligt?
- Wo liegen die Step Definitions?
- Wie werden Steps und Step Definitions zugeordnet?
- Wie werden Parameter oder gar Tabellen �bergeben?


#### Aufgabe 2: Neues Scenario ausdenken
Scenarios zu entwickeln ist Teamarbeit! F�hren Sie diese Aufgabe also bitte mit einem Partner 
durch. Diskutieren und Argumentieren ist erw�nscht.

Denken Sie sich ein neues Scenarion zum Thema Shopping List aus. Formulieren Sie
das Scenarion in Form eines Gherkin Features.

Hier ein paar Anregungen:
- Shopping Liste um Eintr�ge erg�nzen
- Shopping Liste kategorisieren, zum Beispiel "Metzger", "Markt", ...
- Warnhinweis wenn als Menge 0 eingetragen ist

Einigen Sie sich mit Ihrem Partner darauf wie Sie ihre Anforderung ganz konkret notieren.

#### Aufgabe 3: Ausf�hren des eigenen Scenarios
F�hren Sie nun Ihre eigenes Scenarion aus Unit Test aus. Entwicklen Sie nach und nach den
Code hinter dem Scenario, bis der Unit Test bestanden wird.

Gehen Sie dazu folgenderma�en vor:
- F�hren Sie die Tests aus (ohne vorher Code zu schreiben!!).
- Was ist passiert, d.h. schlagen die Tests fehl?
- Erg�nzen Sie nun nach und nach die Step Definitions f�r Ihr Scenario.
- Schreiben Sie ebenfalls nach und nach den Code der Ihr Scenarion realisiert.

#### N�chste Schritte
Sind Sie auf den Geschmack gekommen und wollen noch mehr kennen lernen,
so finden Sie hier Anregungen:
- Wie k�nnen Tabellen in Scenarien verwendet werden.
- �bergeben Sie Parameter. Fangen Sie mit einfachen Parametern an und Arbeiten
  Sie sich bis zu Objekten vor.
- Erzeugen Sie einen Report mit Cucumber JVM.