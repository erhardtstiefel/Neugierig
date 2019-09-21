# Neugierig bis zum gehtnichtmehr ...
<b>Versuch eines 77-jährigen das Programmieren zu lernen.</b>

Kann jemand in unserem Alter noch programmieren lernen? Und das schrittweise Erlernte evtl. in einem Team älterer Menschen praktizieren?
<br><b>Ich bin zu Beginn des Versuchs 77 und will es wissen.</b>

Den Einstieg fand ich durch das Projekt Human Connection https://human-connection.org/ - von dem ich begeistert bin. Um mit meinem im Beruf erlernten Wissen das Projekt <b>vielleicht</b> unterstützen zu können, habe ich mir die 4 Videos auf YouTube, beginnend mit 'Einführung in Open Source Entwicklung - Beispiel Human Connection #1' angesehen und - habe (fast) nur Bahnhof verstanden. 
<br>Wer es auch mal so versuchen will kann ja hier beginnen https://www.youtube.com/watch?v=GDst_MqRSdQ&t=8s

Nun - soviel hatte ich mitbekommen: <b>Man arbeitet auf der Entwicklungs-Plattform GitHub zusammen!</b>

Deshalb habe ich mich zunächst 'auf meine Art' etwas über Github schlau gemacht.
<br>Zunächst mal da, wo ich immer zuerst nachsehe: bei wikipedia um einen Überblick zu bekommen https://de.wikipedia.org/wiki/GitHub
Dann suchte ich nach einer deutschen Anleitung um die Fachbegriffe aus den Videos nachlesen und verstehen zu können. Eine fand ich von der Computer-Zeitschrift CHIP https://praxistipps.chip.de/github-tutorial-diese-basics-muessen-sie-koennen_5078 

Beim Studium dieses 'Praxitipps' kann man schon mal testen, ob man überhaupt Lust am 'Programmieren' hat bzw. es erlernen möchte. Für junge lernbereite und ehrgeizige Menschen sicher ein guter Einstieg. Ich wollte aber wissen, ob man das auch noch im Alter lernen kann? Also installierte ich mir von hier https://desktop.github.com/ die Benutzeroberfläche für Windows herunter.

Hiebei halfen mir meine Englisch Kenntnisse und die Übung im Installieren von Programmen (heute sagt man auch Apps) auf dem PC.
Das beherrschen die meisten jungen Leute. Bei unserer Generation vielleicht nicht so viele. Ist aber noch nicht entscheidend, denn wenn man googlen kann, ist das alles kein Hindernis und erlernbar.

Um sich bei GitHub anmelden zu können, muss man natürlich erstmal registriert sein. Das macht man hier https://github.com/ 
Nach dem Login begann die Anwendung 'GitHub Desktop' nach Repositories zu suchen, und - fand meine "Neugierig" hier https://github.com/erhardtstiefel/Neugierig/edit/master/README.md Wow!

Da erinnerte ich mich, dass ich vor einiger Zeit schon einmal einen Versuch startete und mir das benötigte Git von hier https://git-scm.com/downloads installiert hatte um direkt bei GitHub reinschnuppern zu können.
Dabei bin ich dieser Anleitung https://guides.github.com/activities/hello-world/ gefolgt und hatte mit dem Repository (=Projekt)  "Neugierig" begonnen, die Arbeitsweise auf GitHub zu erlernen ...

Wie es weiter ging findet ihr immer in meinem Blog https://www.erhardt-stiefel.de/

# Weiter ... Teil 1
<b>Wie es weiter ging (Teil1)</b><br>
Was ich bisher schrieb ist bei GitHub im <B>master</b> branch gespeichert. Alles was jetzt dazu kommen soll, schreibe ich zunächst in einen neuen branch, der später dem master zugefügt wird, sobald er <b>commited</b> ist. Aber der Reihe nach.

1. Das Projekt 'Neugierig' ist "nur" eine README.md Datei, d.h. eigentlich nur Kommentar in simplem Textformat. Na ja,  stellenweise verwende ich einige HTML statements (weil ich vor vielen Jahren mal ein wenig damit experimentierte), um wichtige Begriffe hervorzuheben. Um eine Textdatei zu bearbeiten braucht man eigentlich kein GitHub. Aber bei allen Projekten in GitHub wird die README.md genutzt, um den Fortschritt des Projekts schrittweise für andere Leser zu dokumentieren. Andere Leser? Ja. Das Projekt ist <b>öffentlich</b> und kann von jedem eingesehen werden. Schließlich will man ja Interessierte finden, - die mitarbeiten.

2. Wenn wir mal zu zweit (oder mehr) an meinem Repository arbeiten, kann jeder an einem anderen branch arbeiten, oder auch etwas im master korrigieren. Denn <b>ein neuer branch ist stets eine Kopie des master!</b> Allerdings wird die Ergänzung oder die Korrektur im neuen branch erst in den master übernommen, wenn er commited wurde, d.h. der verantwortliche Projektleiter seinen Segen dazu gibt.
Denn: Es muss zusammen passen und eine bestimmte Funktion erfüllen. Bei Text ist das nicht so kritisch und da gibt es viele Formulierungen für die gleiche Aussage. Wenn es aber mal ans Programmieren geht, dann ist der Prozessor der Leser und wenn der den Programmcode nicht versteht, - geht eben nichts.

Ich bin mir bewußt, dass "alte Hasen" - damit meine ich jetzt erfahrene GitHub User - über meine Erläuterungen hier schmunzeln, aber ich lerne am besten, wenn ich aufschreibe was ich meine verstanden zu haben und hoffe bei Human Connection oder 8select einen Mentor zu finden, der ein Lektor wird. Ausserdem schreibe ich dies ja nicht für alte Hasen, sondern für jung gebliebene Rentner! Vielleicht liest dies ja auch schon bald einer davon, der mich unterstützen kann und will. <br>Wunder gibt es immer wieder ... sang Katja Ebstein schon 1970 im Eurovison Song Contest.</b> 

Nachdem ich bis hierher geschrieben hatte, genügte ein Klick auf den Button 'Commit Changes' um die master-Kopie und die Ergänzungen dazu, im neuen branch mit der (default-)Variante: Commit directly, zusammen zu fassen. Weil ich das Projekt (noch) allein fortschreibe, hätte ich das natürlich auch gleich so mit dem master branch machen können. Aber um zu lernen wie man es im Team machen würde, wähle ich jetzt die zweite Variante und starte einen <b>pull request</b>, also eine Angebot meines neuen branches zum commitment.

Die nächsten Schritte vom pull request (zur Verfügung stellen des branches) bis zum Merge (Verschmelzung von master und branch), bieten noch mehrere Möglichkeiten der Kommunikation zwischen dem "Programmierer" der den branch anbietet und dem "Projektleiter" der ihn akzeptieren soll, einschließlich Korrekturmöglichkeiten durch patches (kleine Änderungen). Diese Sequenz muss ich noch einige mal üben, bevor ich mir einen Mentor suche  
