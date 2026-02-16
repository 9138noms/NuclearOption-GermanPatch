# Nuclear Option – Deutscher Patch (Localization Patch)

Ein deutsches Übersetzungsmod für Nuclear Option. Funktioniert als BepInEx-Plugin und übersetzt UI, Enzyklopädie, Hinweise und Tooltips — insgesamt **1.447 Einträge**.

## Voraussetzungen

- [Nuclear Option](https://store.steampowered.com/app/2230590/Nuclear_Option/) (Steam, Early Access 0.32.5+)
- [BepInEx 5.x](https://github.com/BepInEx/BepInEx/releases)

## Installation

1. Installieren Sie **BepInEx 5.x** im Spielordner.
   ```
   Beispiel: C:\Program Files (x86)\Steam\steamapps\common\Nuclear Option\
   ```

2. Starten Sie das Spiel **einmal** und beenden Sie es wieder. (Dadurch wird die BepInEx-Ordnerstruktur erstellt)

3. Kopieren Sie alle Dateien aus diesem Repository nach:
   ```
   [Spielordner]\BepInEx\plugins\LocalizationPatch\
   ```
   > Falls der Ordner „LocalizationPatch" nicht existiert, erstellen Sie ihn manuell.

4. Starten Sie das Spiel — die **deutsche Übersetzung wird automatisch angewendet**.

## Enthaltene Dateien

| Datei | Beschreibung |
|-------|-------------|
| `LocalizationPatch.dll` | Patch-Plugin |
| `de.json` | Deutsche Übersetzungsdaten (1.447 Einträge) |

## Tastenkürzel im Spiel

| Taste | Funktion |
|-------|----------|
| `F10` | Debug-Overlay ein-/ausblenden |
| `Strg+F10` | Übersetzungsdaten neu laden (Hot Reload) |

## Hinweise

- Missionsnamen und Fraktionsnamen (PALA, BDF) bleiben auf Englisch.
- Bei Problemen können Sie in der Datei `BepInEx\config\com.yuulf.localizationpatch.cfg` die Sprache manuell auf `Language = de` setzen.
