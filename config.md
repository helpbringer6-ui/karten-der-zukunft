# Konfiguration der AR-Umgebung

## Schritte zur Konfiguration

1. Öffne die `config.json`-Datei und passe die Einstellungen an:
   - `ar_framework`: Wähle zwischen "ARKit" oder "ARCore".
   - Füge API-Keys für externe Dienste hinzu.
   - Konfiguriere die Kartendatenquellen.

2. Stelle sicher, dass alle Berechtigungen für Standortdienste und Kamera aktiviert sind.

3. Teste die Konfiguration, indem du den Beispieltest ausführst:
   ```bash
   npm run test
   ```

4. Überprüfe die Ausgaben des Tests, um sicherzustellen, dass keine Fehler auftreten.

## Zusätzliche Hinweise
- Stelle sicher, dass dein Gerät in einem gut beleuchteten Bereich ist, um optimale Ergebnisse zu erzielen.
- Es wird empfohlen, die Konfiguration nach jeder Änderung erneut zu testen.