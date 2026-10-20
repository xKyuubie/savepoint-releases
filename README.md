# Savepoint – Downloads

Backup und Wiederherstellung für deinen Windows-PC – damit nach dem Neuaufsetzen alles schnell wieder so ist wie vorher.

**Herunterladen:** rechts unter **Releases** die neueste Version öffnen und `Savepoint.exe` herunterladen.
Was neu ist, steht in [CHANGELOG.md](CHANGELOG.md).

## Installieren

1. `Savepoint.exe` herunterladen und doppelklicken.
2. Windows zeigt beim ersten Mal **„Der Computer wurde durch Windows geschützt“**. Das kommt, weil Savepoint kein
   kostenpflichtiges Zertifikat hat. Auf **„Weitere Informationen“** und dann **„Trotzdem ausführen“** klicken.
3. Savepoint fragt beim ersten Start, wo die Backups liegen sollen. Am besten ein Cloud-Ordner (z.B. OneDrive) oder
   eine externe Festplatte – **nicht** das Laufwerk C:, das wird beim Neuaufsetzen gelöscht.
4. Für das automatische Backup: Seite **„Zeitplan“** → einrichten. Savepoint installiert sich dabei nach
   `C:\Program Files\Savepoint` und erscheint unter Windows-Apps.

Deinstallieren: Windows-Einstellungen → Apps → Savepoint → Deinstallieren. Deine Backups bleiben erhalten.

## Datenschutz

- Savepoint fragt beim Start bei GitHub nach einer neuen Version (in den Einstellungen abschaltbar) und sendet sonst
  nichts ins Internet. Deine Backups bleiben am Speicherort, den du wählst.
- Ein Fehlerbericht wird nie von selbst gesendet. Du siehst ihn vorher; Benutzernamen, Ordner- und Dateinamen sind
  daraus entfernt.
- Passwörter, Logins und Cookies werden **nie** gesichert.

## Voraussetzungen

Windows 10 (ab Version 2004) oder Windows 11, 64 Bit. Sonst nichts.

## Problem gefunden?

Am einfachsten in Savepoint unter **Einstellungen → Updates → „Problem melden …“**: Savepoint erstellt einen
Fehlerbericht ohne Persönliches und öffnet hier eine neue Meldung, in die du ihn einfügst.

Passt ein Update nicht, geht es unter **Einstellungen → Updates** zurück zur vorherigen Version.
