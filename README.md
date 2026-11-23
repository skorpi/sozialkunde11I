# Eine Lernapp bauen oder für einen Anlass üben

Mit dieser Vorlage baust du eine kleine Lernapp, ohne etwas auf deinem Rechner zu installieren. Ein KI-Agent hilft dir
im Browser. Du beschreibst, was du brauchst, er baut und prüft die App. Die Anleitung mit Bildern steht auf lernapps.net:
[Mit Codespaces bauen](https://lernapps.net/apps/build/codespaces/) und [Mit Codespaces üben](https://lernapps.net/practice/codespaces/).

## Was du brauchst

- Ein kostenloses GitHub-Konto.
- Ein Abo oder einen Schlüssel für einen KI-Agenten: **Claude** (Claude Pro oder höher) oder **ChatGPT** (Codex). Die
  Kosten trägst du selbst. lernapps.net bezahlt keine KI-Nutzung.

## So geht es

1. Klicke oben auf **Use this template** und dann auf **Create a new repository**. Gib einen kurzen Namen für deine
   App ein, zum Beispiel `bruchrechnen`. Das Repository gehört dir.
2. Öffne dein neues Repository. Klicke auf **Code**, dann auf **Codespaces** und auf **Create codespace on main**.
   GitHub startet eine fertige Arbeitsumgebung im Browser. Das dauert einige Minuten. Diese Anleitung öffnet sich
   dort von selbst.
3. Melde dich bei deinem Agenten an (siehe unten).
4. Sage dem Agenten, was du möchtest: eine App zum Teilen bauen oder für einen Anlass üben, etwa die nächste Arbeit.
   Er fragt nach Thema, Klassenstufe und dem, was Lernende tun sollen. Er legt die App in diesem Ordner an, nicht in
   einem Unterordner.
5. Der Agent zeigt dir Zwischenstände. Du bestätigst oder bittest um Änderungen. Am Ende prüft er die App und hilft dir,
   sie bei lernapps.net einzureichen.

## Anmelden

Mit Bildern: [Mit Codespaces bauen](https://lernapps.net/apps/build/codespaces/) auf lernapps.net.

**Claude:** Klicke oben rechts im Editor auf das Symbol von Claude. Rechts öffnet sich ein Fenster. Wähle **Claude.ai
Subscription** und dann **Continue in browser**. Beim ersten Mal klappt das meist nicht von selbst: Der Browser meldet
„Diese Seite ist nicht erreichbar“ (Adresse `localhost`). Das ist im Codespace normal. Kopiere die Adresse aus dem Fenster
von Claude (Knopf neben dem Feld) und füge sie noch einmal in einem neuen Tab deines Browsers ein. Folge dann den
Hinweisen auf der Seite. Zeigt sie einen Code, kopiere ihn und füge ihn im Fenster von Claude ein.

**ChatGPT (Codex):** Klicke oben rechts im Editor auf das Symbol von Codex. Wähle nicht **Mit ChatGPT anmelden**, sondern
**Weitere Optionen** und dann die Anmeldung per Gerätecode. Du musst sie in ChatGPT einmal erlauben, unter Einstellungen im
Bereich Sicherheit. Teile einen Gerätecode mit niemandem.

Beim Start fragt der Editor, ob du den Autoren der Dateien in diesem Ordner vertraust. Klicke auf **Ordner vertrauen und
fortfahren**. Ohne dieses Ja bleiben die Erweiterungen für Claude und Codex ausgeschaltet. Bei der Anmeldung fragt er
manchmal, ob er eine Webseite öffnen darf: Klicke auf **Öffnen**. Das sind Rückfragen des Editors, keine Warnungen vor
deiner App.

Das Terminal unten brauchst du wahrscheinlich nicht. Du kannst es minimieren. Wer `claude` oder `codex` lieber im Terminal
nutzt, installiert es mit `npm install --global @anthropic-ai/claude-code` oder `npm install --global @openai/codex`.

## Pausieren und später weitermachen

- Ein Codespace hält nach 30 Minuten ohne Eingabe von selbst an. Deine Dateien bleiben erhalten, auch Änderungen, die
  noch nicht gespeichert sind. Laufende Arbeit des Agenten und die Vorschau werden beendet.
- Zum Weitermachen öffne [github.com/codespaces](https://github.com/codespaces) und klicke bei deinem Codespace auf
  **Open**. Das dauert eine Minute.
- Ein Codespace, den du 30 Tage lang nicht öffnest, wird gelöscht. Bitte den Agenten deshalb am Ende einer Sitzung, deine
  Arbeit auf GitHub zu sichern.
- Ein angehaltener Codespace kostet keine Rechenzeit, nur ein wenig Speicher. Die Einstellungen für die Wartezeit und die
  Aufbewahrung findest du bei GitHub unter **Settings**, **Codespaces**.

## Gut zu wissen

- GitHub gibt kostenlosen Konten jeden Monat etwa 60 Stunden Codespace-Zeit. Beende den Codespace, wenn du fertig bist.
- Der Agent darf in deinem Codespace alles tun und sieht das ganze Internet. Gib dort keine Passwörter und keine Daten
  von Schülerinnen und Schülern ein.
- Deine Texte gehen an den Anbieter des Agenten (Anthropic oder OpenAI). Schreibe keine Namen von Lernenden hinein.
- Die fertige App sammelt keine Daten und läuft ohne Konto im Browser. Das prüft lernapps.net, bevor sie erscheint.
