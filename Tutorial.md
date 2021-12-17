# Github Tutorial

DISCLAIMER: dieses tutorial ist wirklich unglaublich unnötig ausführlich lol wer hier was falsch macht ist dumm

## 1. auf github einloggen:
1. gehe auf github.com

### Wenn du noch keinen github account hast:
2. klicke rechts oben in der ecke auf "Registrieren"
3. wähle bei "Benutzername" bzw. "Username" einen benutzernamen aus
4. gebe bei "email addresse" deine email addresse ein
5. bei "passwort" musst du dir ein passwort ausdenken
6. bei "verify your account" bzw. "account verifizieren" musst du ein kleines rätsel lösen sodass github weis das du ein mensch bist.
7. klicke auf "create account" bzw. "account erstellen"
8. danach kommt eine seite wo du einen 8-stelligen code eingeben musst dieser wurde dir per email zugeschickt
9. -> also gebe den code aus der email dort ein
10. jetzt stellt github euch fragen über wie ihr github benutzen wollt ihr müsst aber nur die frage mit wievielen du arbeiten willst beantworten 
11. den rest einfach durch klicken
12. am ende auf "Continue for free" klicken 
13. jetzt habt ihr einen github account
14. schickt mir(StarMiner99) jetzt euren GitHub benutzernamen, den ihr bei schritt 3 ausgewählt habt, über discord

### Wenn du bereits einen github account hast:
2. klicke recht oben in der ecke auf "Einloggen"
3. gebt eure email bzw. euren benutzernamen ein und euer passwort
4. drückt auf "sign in" bzw. "Einloggen"
5. jetzt schickt mir (StarMiner99) euren GitHub benutzernamen über discord

## 2. Das Texture pack aufrufen

1. sobald ich meine discord nachrichten gelesen habt und euch hinzugefügt habe gekommt ihr eine email von GitHub
2. -> in dieser email steht sowas ähnliches wie: "StarMiner99 hat dich zu StarMiner99/UselessTexturePack eingeladen"
3. in dieser email musst du auf "View invitation" bzw. "Einladung anzeigen" klicken
4. sobald du das tust öffnet sich ein neuer tab 
5. in diesem tab musst du auf "Accept invitation" bzw. "Einladung annehmen" drücken.
6. sobald du das tust wird sich die webseite von dem texture pack öffnen.

### 2.1 Das Texture pack herunterladen
7. wenn du auf dieser webseite vom texture pack bist kannst du auf "Code" drücken
8. und danach auf "Download ZIP" drücken
9. diese datei musst du entpacken
10. in der entpackten datei befindet sich ein ordner in diesem ordner befindet sich das texture pack
11. das einfach kopieren und dan in den minecraft texture pack ordner rein machen.

### 2.2 Geplante änderungen ansehen und dafür voten bzw. kommentieren
7. wenn du dir die geplanten änderungen ansehen willst kannst du auf den reiter "Pull requests" gehen
8. dort befindet sich eine liste mit geplanten änderungen wie zum beispiel die änderung "beispiel"
9. klicke auf die änderung die du dir ansehen willst
10. hier seht ihr eine beschreibung der änderung die vorgenommen wurde und hoffentlich auch ein paar screenshots die der jenige der die änderung gemacht hat reingestellt hat
11. wenn ihr für oder gegen die änderung voten wollt könnt ihr das tun indem ihr auf die nachricht mit einem "daumen hoch" oder mit einem "daumen runter" reagiert
12. wenn ihr euren kommentar dazu abgeben wollt könnt ihr das auch machen
13. der knopf "Merge pull request" führt dazu das die änderungen vorgenommen werden also bitte nicht sofort diesen knopf drücken sondern erst wenn DAFÜR gevoted wurde bzw. die änderung nur ein kleiner bugfix ist.
14. wenn ihr die änderung austesten wollt und sie herunterladen wollt könnt ihr zu "*3. änderungen vornehmen und herunterladen*" gehen

## 3. Änderungen vornehmen und herunterladen

OPTION 1:
### 3.1.1 Frag jemanden lol
1. frag StarMiner99 oder Schmensch oder irgendjemand der weis wie das geht weil das muss man leider mit command line (cmd.exe) machen
2. schick einfach die änderung an ihn/sie über discord und der/die macht das dan einfach.
3. wenn du ne änderung austesten willst frag einfach danach und schick den link von der änderung rein.

OPTION 2 (achtung kann etwas kompliziert werden):
### 3.1.2 GitHub CLI und Git herunterladen
#### 3.1.2.1 Installieren von git und github cli:
1. lade dir git herunter und installier es: https://git-scm.com/download/
2. lade dir gitub cli herunter: https://github.com/cli/cli/releases/tag/v2.3.0
3. wähle halt die passende datei unten aus (.msi für windows, .deb für linux, der rest steht im namen)
4. und dan installier sie indem du die heruntergeladene datei doppelklickst

#### 3.1.2.2 Das Texture pack herunterladen sodass man es modifizieren kann (muss man nur ein einziges mal machen)
1. WENN DU KEINE AHNUNG HAST WIE DU mit "cd" und mit "dir" bzw. "ls" arbeiten musst dan wird dir das folgende nichts bringen also frag jmd wie das funktioniert.
2. öffne ein "terminal" bzw. "cmd.exe" für windows 
3. gehe mit "cd <dateipdaf>" in einen ordner wo das texturepack heruntergeladen werden soll
4. ACHTUNG: ein unterordner wird automatisch erstellt
5. jetzt gebe folgendes ein: `gh auth login`
6. GitHub CLI wird dir jetzt ein paar fragen stellen und dir anweisungen geben für wie du dich einlogst, folge diesen einfach.
7. sobald du dich eingelogt hast kannst du jetzt anfangen die repo herunterzuladen:
8. gebe ein: `gh repo clone StarMiner99/UselessTexturePack`
9. GitHub CLI hat jetzt einen neuen ordner namens "UselessTexturePack erstellt"
10. in diesem ordner befindet sich das texture pack
11. was du noch machen musst:
12. setze dein git benutzername und deine email (das ist kein einloggen)
13. führe dazu einfach folgendes in dem terminal bzw. cmd.exe aus:
14. `git config --global user.email "you@example.com"` natürlich you@example.com ersetzen mit deiner email
15. `git config --global user.name "Your Name"` Your Name musst du mit deinem namen ersetzen

#### 3.1.2.3 Änderungen ausprobieren bzw. genauer anschauen
1. hierfür brauchst du erneut das terminal bzw. die cmd.exe
2. gehe mit "cd" in den ordner des Texturepack also `cd C:\User\IrgendeinOger\random\shit\UselessTexturePack` oder wo auch immer du es runtergeladen hast
3. jetzt kannst du auf der webseite der änderung auf den knopf "Code" oben rechts in der ecke gehen
4. dort befindet sich eine zeile code den du dir jetzt kopieren kannst und eingeben kannst
5. der code sollte so aussehen: `gh pr checkout <änderungID>`
6. geh wieder in dein terminal bzw. cmd.exe und geb das ein
7. die änderung wird automatisch vorgenommen ABER nur an deinem PC
8. um wieder zurück zum normalen zu kehren kannst du einfach `git checkout master` eingeben
9. um das Texturepack auf die neuste version zu bringen musst du `git pull` eingeben.
  
#### 3.1.2.4 Änderungen vornehmen
1. als aller erstes bevor du eine änderung machst:
2. gehe in ein terminal bzw. cmd.exe und gehe wieder mit "cd" in den ordner des Texturepacks
3. immer bevor du eine änderung machst musst du das Texturepack auf die neuste version bringen das machst du mit: `git pull`
4. jetzt musst du als aller erstes eine neue "abzweigung" (branch) erstellen für deine änderung
5. `git branch <name der abzweigung>` der name kann irgendwas random sein aber er sollte nicht bereits existieren. Auserdem musst du zusätzlich `git push --set-upstream origin <name der abzweigung>` machen.
6. das kannst du nachschauen indem du auf die webseite des Texturepacks gehst und dan links oben auf "master" klickst und schaust ob es dort schon eine abzweigung mit diesen namen gibt
7. merke dir: "master" ist immer die standart abzweigung
8. wenn du jetzt `git branch` eingibst kannst du alle abzweigungen sehen die mit dem sternchen davor hast du momentan ausgewählt
9. wähle die richtige abzweigung aus: 
10. um eine abzweigung aus zu wählen musst du folgendes tun: `git checkout <name der abzweigung>`
11. wenn du jetzt erneut `git branch` ausführst wirst du sehen, dass die abzweigung ausgewählt wurde

Die folgenden schritte kannst du so oft wiederholen bis du zufrieden bist:

12. jetzt kannst du alle änderungen vornehmen die du vornehmen willst.
13. sobald du fertig bist musst du die änderungen "registrieren" (adden) die einfachste möglichkeit ist einfach: `git add *` wichtig * nicht ersetzen
14. das musst du dann, ich nenn es mal "abspeichern" (commiten) indem du eingibst: `git commit -m "beschreibung deiner änderung"`
15. nun musst du die änderung nur noch hochladen mit: `git push`

Bis hier wiederholen (das geht auch noch nach dem "Pull request" noch das wird dan automatisch hinzugefügt)

16. jetzt kannst du auf die website von dem Texturepack gehen und auf den reiter "Pull request"
17. dort kannst du jetzt auf "New pull request" gehen
18. hier musst du oben bei "base" "master" auswählen und bei "compare" deine abzweigung die du soeben erstellt hast
19. jetzt kannst du auf "Create Pull request" gehen
20. im nächsten fenster solltest du eine beschreibung angeben und einen titel der änderung wenn du willst auch mit bildern
21. sobald du fertig bist drück einfach wieder den grünen knopf
22. jetzt kannst du auf discord ne nacricht mit dem link der änderung schreiben und alle können dafür voten wenn sie wollen
23. sobalt dafür gevoted wurde kannst du auf "Merge pull request" gehen.
24. wenn aber dagegen gevoted wird, wird die änderung nicht vorgenommen und deshalb auch nicht "gemerged" also dan darfst du NICHT diesen knopf drücken
  
