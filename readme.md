# LB 324

## Aufgabe 2

Für die lokale Qualitätssicherung wirdpre-commit verwendet.

Zuerst wird pre-commit installiert: 
# LB 324

## Aufgabe 2

Für die lokale Qualitätssicherung wird `pre-commit` verwendet.

Zuerst wird `pre-commit` installiert:

```bash
pip install pre-commit

## Aufgabe 4

Die Applikation wurde auf Render ausgeliefert, da das bereitgestellte
Azure-for-Students-Abonnement deaktiviert war.

### URL der laufenden Applikation

https://frailegabriellb-324.onrender.com

### Passwort als Umgebungsvariable

Die lokale `.env`-Datei wird nicht auf GitHub hochgeladen.

Auf Render wurde unter den Environment Variables die Variable
`PASSWORD` erstellt.

Als Wert wurde der GitHub-Benutzername verwendet.

Die Flask-Applikation liest diesen Wert mit:

`os.getenv("PASSWORD")`

Dadurch muss das Passwort nicht im Quellcode gespeichert werden.

### Automatische Auslieferung

Der Render Web Service ist mit dem GitHub-Repository verbunden.

Als Deployment-Branch wurde `main` ausgewählt. Änderungen auf `main`
werden dadurch automatisch erneut gebaut und ausgeliefert.

Build Command:

`pip install -r requirements.txt`

Start Command:

`gunicorn app:app`