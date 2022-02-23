# Robocode

## Sett opp prosjektet i IntelliJ (Anbefalt)

1. Installer [Robocode](https://sourceforge.net/projects/robocode/files/robocode/1.9.3.7/robocode-1.9.3.7-setup.jar/download).
1. Installer [IntelliJ](https://www.jetbrains.com/idea/download/).
1. Last ned og pakk ut [prosjektmalen](https://github.com/netcompanyno/robocode-templates/archive/master.zip).
1. Åpne enten `robocode-java` eller `robocode-kotlin` i IntelliJ.
1. Endre pakkenavnet i `ExampleRobot` fra `example` til ditt lagnavn. Tips: Shift-F6.
1. Endre klassenavnet fra `ExampleRobot` til ditt lagnavn. Tips: Shift-F6.

## Sett opp prosjektet i VS Code (Alternativt)

1. Installer [Robocode](https://sourceforge.net/projects/robocode/files/robocode/1.9.3.7/robocode-1.9.3.7-setup.jar/download).
1. Installer [VS Code](https://code.visualstudio.com/download) og utvidelsen `Language Support for Java(TM) by Red Hat`.
1. Last ned og pakk ut [prosjektmalen](https://github.com/netcompanyno/robocode-templates/archive/master.zip).
1. Åpne enten `robocode-java` eller `robocode-kotlin` i VS Code.
1. Endre pakkenavnet i `ExampleRobot` fra `example` til ditt lagnavn. Navnet på mappen må endres til det samme.
1. Endre klassenavnet fra `ExampleRobot` til ditt lagnavn. Tips: F2.

## Bygg roboten

1. Om du har installert Robocode utenom standard filsti, oppdater `ext.robots` i `build.gradle`.
1. Om du har endret klassenavn eller pakkenavn, kjør `Tasks -> build -> clean` fra Gradle-panelet i IntelliJ eller `./gradlew clean` fra terminalen.
1. Kjør `Tasks -> other -> export` fra Gradle-panelet i IntelliJ eller `./gradlew export` fra terminalen.
1. Stopp eventuell pågående kamp i robocode. Dette hindrer at du må kjøre `Options -> Clean robot cache`.
1. Start ny eller restart siste kamp i robocode

## Nyttige hurtigtaster

### IntelliJ
* `Shift-F6` Gi nytt navn
* `Shift-F10` Bygg på nytt
* `Ctrl-O` Overstyr funksjon
* `Ctrl-Q` Vis dokumentasjon
* `Ctrl-Alt-L` Formater koden

### VS Code
* `F2` Gi nytt navn
* `Ctrl-S` Lagre
* `Ctrl-Shift-I` Formater koden

### Robocode
* `Ctrl-N` Ny kamp
* `Alt-S` Stopp
* `Alt-T` Restart

## Innlevering
Gå til [robocode.no](http://robocode.no), og registrer lag/logg inn.

Last opp .jar-filen.

Se til at brukernavnet ditt/deres nå er grønt på storskjermen.

## Nyttige lenker
* [RoboWiki](http://robowiki.net/): [Tutorials](http://robowiki.net/wiki/Tutorials), [Game Physics](http://robowiki.net/wiki/Robocode/Game_Physics), [Graphical Debugging](http://robowiki.net/wiki/Robocode/Graphical_Debugging)
* [Robocode API Javadoc](http://robocode.sourceforge.net/docs/robocode/): [Robot](http://robocode.sourceforge.net/docs/robocode/robocode/Robot.html), [AdvancedRobot](http://robocode.sourceforge.net/docs/robocode/robocode/AdvancedRobot.html)
* [Robocode tutorial fra itenium](https://itenium.be/blog/design/robocode-tutorial/) (uoffisiell)
