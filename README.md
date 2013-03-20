[Stuttgarter Test Tage 2013](http://www.jugs.org/tt2013/)
=====================

Übung: Gurkensalat statt Spaghetticode
---------------------

### Vorbereitung
Clonen Sie das Github Repository `git@github.com:remast/TestTage2013_Cucumber.git`.
Dort finden Sie den Code und die Instruktionen zur Übung.

Alternativ können Sie das Repository auch als Zip-Archiv herunterladen:
https://github.com/remast/TestTage2013_Cucumber/zipball/master

Öffnen Sie nun Eclipse.

Importieren Sie dort das Projekt `cucumber.java-helloworld` aus dem Github Repository.
Gehen Sie dazu auf "File > Import > Existing Projects into Workspace" und wählen Sie 
dann das Verzeichnis `cucumber.java-helloworld` aus.

Nun sind Sie bereit mit der Übung zu beginnen.

### Übungen

#### Aufgabe 1: BDD Test ausführen
Führen Sie die BDD Tests aus dem Beispielprojekt `cucumber.java-helloworld` aus. 
Die Konfiguration hierfür ist bereits im Eclipse Projekt vorhanden.

Führen Sie unter Eclipse die JUnit Launch Konfiguartion "RunCukesTest" aus.
Diese finden Sie im Menü "Run > RunCukesTest".

Öffnen Sie die *.feature Datei mit den Szenarien. Schauen Sie sich die verschiedenen Szenarien an. 

Verfolgen Sie die Ausführung des Scenarios. Gehen Sie folgenden Fragen nach:
- Welche Klassen sind beteiligt?
- Wo liegen die Step Definitions?
- Wie werden Steps und Step Definitions zugeordnet?
- Wie werden Parameter oder gar Tabellen übergeben?


#### Aufgabe 2: Neues Scenario ausdenken
Scenarios zu entwickeln ist Teamarbeit! Führen Sie diese Aufgabe also bitte mit einem Partner 
durch. Diskutieren und Argumentieren ist erwünscht.

Denken Sie sich ein neues Scenarion zum Thema Shopping List aus. Formulieren Sie
das Scenarion in Form eines Gherkin Features.

Hier ein paar Anregungen:
- Shopping Liste um Einträge ergänzen
- Shopping Liste kategorisieren, zum Beispiel "Metzger", "Markt", ...
- Warnhinweis wenn als Menge 0 eingetragen ist

Einigen Sie sich mit Ihrem Partner darauf wie Sie ihre Anforderung ganz konkret notieren.

#### Aufgabe 3: Ausführen des eigenen Scenarios
Führen Sie nun Ihre eigenes Scenarion aus Unit Test aus. Entwicklen Sie nach und nach den
Code hinter dem Scenario, bis der Unit Test bestanden wird.

Gehen Sie dazu folgendermaßen vor:
- Führen Sie die Tests aus (ohne vorher Code zu schreiben!!).
- Was ist passiert, d.h. schlagen die Tests fehl?
- Ergänzen Sie nun nach und nach die Step Definitions für Ihr Scenario.
- Schreiben Sie ebenfalls nach und nach den Code der Ihr Scenarion realisiert.

#### Nächste Schritte
Sind Sie auf den Geschmack gekommen und wollen noch mehr kennen lernen,
so finden Sie hier Anregungen:
- Wie können Tabellen in Scenarien verwendet werden.
- Übergeben Sie Parameter. Fangen Sie mit einfachen Parametern an und Arbeiten
  Sie sich bis zu Objekten vor.
- Erzeugen Sie einen Report mit Cucumber JVM.