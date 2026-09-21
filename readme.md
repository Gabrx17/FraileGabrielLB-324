# LB 324

## Aufgabe 2

Für die lokale Qualitätssicherung wird `pre-commit` verwendet.

Zuerst wird `pre-commit` installiert:

```bash
pip install pre-commit
```

Danach werden die Hooks für Commit und Push installiert:

```bash
pre-commit install --hook-type pre-commit
pre-commit install --hook-type pre-push
```

Bei jedem Commit wird der Python-Code automatisch mit Black formatiert.

Bei jedem Push werden die Tests automatisch mit pytest ausgeführt.

## Aufgabe 4

Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.