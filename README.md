# Robocode

## Sett opp prosjektet

1. Installer [Robocode](https://sourceforge.net/projects/robocode/files/latest/download) og [IntelliJ](https://www.jetbrains.com/idea/download/).
1. Last ned [prosjektmalen som zip](https://github.com/netcompanyno/robocode-templates/archive/master.zip) eller kjør `git clone git@github.com:netcompanyno/robocode-templates`.
1. Åpne enten Java- eller Kotlin-prosjektet i IntelliJ.
1. Endre `ext.robocode` i `build.gradle` til din robocode-mappe. Typisk `C:\\robocode` på Windows, `/Users/<brukernavn>/robocode` på Mac og `/home/<brukernavn>/robocode` på Linux.
1. Endre pakkenavnet i `ExampleRobot` fra `example` til ditt lagnavn. Tips: Sett markøren i navnet eller merk mappen og trykk Shift-F6.
1. Endre klassenavnet fra `ExampleRobot` til noe gøyalt, mystisk, eller fryktingytende. Trikset med Shift-F6 fungerer her også.

## Bygg roboten

1. Om du har endret klassenavn eller pakke, kjør `Tasks -> build -> clean` fra Gradle-panelet i IntelliJ eller `gradlew clean` fra terminalen.
1. Kjør `Tasks -> other -> export` fra Gradle-panelet i IntelliJ eller `gradlew export` fra terminalen.
1. Stopp eventuell pågående kamp i robocode. Dette hindrer at du må kjøre `Options -> Clean robot cache`.
1. Start ny eller restart siste kamp i robocode

## Nyttige hurtigtaster

### IntelliJ
* `Shift-F6` Gi nytt navn
* `Shift-F10` Bygg på nytt
* `Ctrl-O` Overstyr funksjon
* `Ctrl-Q` Vis dokumentasjon
* `Ctrl-Alt-L` Formater koden

### Robocode
* `Ctrl-N` Ny kamp
* `Alt-S` Stopp
* `Alt-T` Restart

## Nyttige lenker
* [RoboWiki](http://robowiki.net/): [Tutorials](http://robowiki.net/wiki/Tutorials), [Game Physics](http://robowiki.net/wiki/Robocode/Game_Physics), [Graphical Debugging](http://robowiki.net/wiki/Robocode/Graphical_Debugging)
* [Robocode API Javadoc](http://robocode.sourceforge.net/docs/robocode/): [Robot](http://robocode.sourceforge.net/docs/robocode/robocode/Robot.html), [AdvancedRobot](http://robocode.sourceforge.net/docs/robocode/robocode/AdvancedRobot.html)
