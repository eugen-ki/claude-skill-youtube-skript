# YouTube-Skript: Titel, Intro und Skript mit Claude Code

Ein Claude-Code-Skill, der dir für ein YouTube-Video Titel, ein 30-Sekunden-Intro und das ganze Skript zum Ablesen schreibt. Er baut auf einem Video aus deiner Nische auf, das nachweislich gut lief, und übernimmt dessen Muster für dein Thema.

## Was du bekommst

- 3 bis 5 Titel mit Suchbegriff vorne und einer klaren Empfehlung.
- Ein Intro Wort für Wort, etwa 30 Sekunden lang.
- Das ganze Skript in Schritten, fertig für den Teleprompter.
- Eine Checkliste für vor der Aufnahme.

## Installieren

1. Oben rechts auf **Code** und dann **Download ZIP** klicken. ZIP entpacken.
2. Im entpackten Ordner liegt der Ordner `youtube-skript`. Kopiere genau diesen Ordner in deinen Skills-Ordner:
   - Windows: `C:\Users\<dein-name>\.claude\skills\`
   - Mac: `~/.claude/skills/`

   Gibt es den Ordner `skills` noch nicht, leg ihn an. Danach liegt die Datei unter `.claude/skills/youtube-skript/SKILL.md`.
3. Claude Code neu starten.

## So benutzt du ihn

Tippe `/youtube-skript` oder sag es einfach in deinen Worten, zum Beispiel:

> Schreib mir ein YouTube-Skript. Ich habe mit Claude Code eine Buchungsseite für mein Studio gebaut.

## Tipp: zuerst dein Profil

Der Skill klingt nach dir, wenn du vorher einmal [mein-profil](https://github.com/eugen-ki/claude-skill-mein-profil) installierst und `/mein-profil` startest. Ohne Profil funktioniert er auch, er stellt dir dann ein paar kurze Fragen.

## Was du brauchst

- [Claude Code](https://claude.com/claude-code).
- Am besten zusätzlich Titel und Anfang von 1 bis 3 Videos aus deiner Nische, die besonders gut liefen. Der Skill erklärt dir, wie du sie findest.

## Gut zu wissen

- Der Skill erfindet keine Zahlen oder Ergebnisse. Was er nicht weiß, steht in `[eckigen Klammern]`. Füll diese Stellen vor dem Veröffentlichen mit echten Angaben.
- Das Ergebnis speichert er als Datei in dem Ordner, in dem du Claude Code gestartet hast.

## Lizenz

MIT, frei nutzbar und veränderbar. Siehe [LICENSE](LICENSE).
