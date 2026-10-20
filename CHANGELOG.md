# Neuigkeiten in Savepoint

Hier steht bei jeder Version, was sich geändert hat. Die neueste Version steht oben.

Gegliedert in **Neu** (neue Funktionen), **Verbessert** (bestehendes geht besser) und **Behoben** (Fehler korrigiert).

## 1.2.0 – 20.10.2026

### Neu
- **Zurück zur vorherigen Version:** Passt ein Update nicht, geht es unter **Einstellungen → Updates** mit einem Klick
  zurück. Die zurückgenommene Version wird danach nicht mehr angeboten, erst die nächste.
- Startet eine neue Version zweimal nicht richtig, fragt Savepoint von selbst, ob es zur vorherigen zurück soll.
- **Problem melden:** Savepoint erstellt einen Fehlerbericht ohne Benutzernamen, Ordner- und Dateinamen. Du siehst ihn
  vorher und entscheidest selbst: kopieren, als Datei speichern oder auf GitHub melden. Gesendet wird nie von selbst.

### Behoben
- Seite „Neuigkeiten“ und Update-Fenster: Der Text war nach dem Update auf 1.1.0 zu klein, und die Abschnitte „Neu“ und
  „Behoben“ waren nicht mehr hervorgehoben.
- Das Update-Fenster wartet jetzt, bis die Ordnerauswahl beim ersten Start geschlossen ist, statt sich darüber zu legen.
- Im Update-Fenster erscheint kein schwarzer Rahmen mehr um die Neuigkeiten.

## 1.1.0 – 19.10.2026

### Neu
- **Updates:** Beim Start schaut Savepoint, ob es eine neue Version gibt, und zeigt dann, was neu ist. Mit „Jetzt
  aktualisieren“ lädt und installiert es die neue Version und startet neu; „Später“ fragt beim nächsten Start wieder.
- Unter **Einstellungen → Updates** lässt sich das Nachfragen ausschalten; „Jetzt nach Updates suchen“ geht trotzdem.
- Jedes Update ist **digital unterschrieben**. Savepoint installiert nur Updates, die wirklich von uns kommen.
- Neue Seite **„Neuigkeiten“** mit allen Versionen. Nach einem Update zeigt Savepoint einmal, was neu ist.

### Behoben
- Beim Einrichten des automatischen Backups aus einer heruntergeladenen `Savepoint.exe` wurde der ganze Ordner, in dem
  sie lag (z.B. Downloads), mit nach „Program Files“ kopiert. Jetzt nur noch Savepoint selbst.

## 1.0.0 – 19.10.2026

Die erste Version für Freunde und Familie.

### Neu
- **Backup mit einem Klick:**
  - eigene Ordner und den Desktop
  - die Liste deiner Programme
  - Einstellungen von Programmen und Launchern
  - Browser-Favoriten
  - Windows- und Gaming-Einstellungen
  - WLAN-Profile
  - Hardware-Infos
- **Automatisches Backup** nach deinem Zeitplan (täglich, wöchentlich, monatlich …), auch für Dateien, die gerade
  in Gebrauch sind. Es werden höchstens 5 automatische Backups behalten.
- **Speicherort frei wählbar:**
  - ein Cloud-Ordner (OneDrive, Nextcloud, Dropbox, Google Drive)
  - eine USB- oder externe Festplatte
  - ein weiteres Laufwerk oder ein NAS
- **Verschlüsselung** mit deinem Passwort (AES-256). Alle 3 Monate erinnert Savepoint an eine kurze Kontrolle, damit
  du es nicht vergisst.
- **Geführte Wiederherstellung** auf dem frisch installierten PC:
  - installiert die Programme wieder (über winget)
  - setzt Einstellungen und Favoriten zurück
  - fragt, wohin deine eigenen Ordner sollen
  - macht nach einem Neustart dort weiter, wo sie war
- **Assistenten** für Dinge, die man nicht automatisch sichern kann:
  - Grafikkarten-Einstellungen (AMD Adrenalin)
  - BIOS-Profil und eine Checkliste passend zu deiner Hardware
- **Anleitung „PC neu aufsetzen“** Schritt für Schritt, auch als Seite zum Abhaken auf dem USB-Stick.
- **Checkliste „Vor dem Neuaufsetzen“** in der Übersicht: Savepoint prüft selbst, was es kann (z.B. aktuelles Backup,
  USB-Stick bereit); den Rest hakst du ab.
- **Windows-Benachrichtigungen** nach dem automatischen Backup, einstellbar.
- **Darstellung:** hell oder dunkel, Akzentfarbe, Schriftgrösse und Abstände wählbar.
- **Unter „Apps“ in Windows** sauber deinstallierbar. Deine Backups bleiben dabei erhalten.

### Nie gesichert (mit Absicht)
- Spiele (lassen sich über die Launcher neu laden)
- Passwörter, Logins und Cookies von Browsern und Launchern
