# Fernweh als echte App installieren 📲

## Variante A – GitHub Pages (empfohlen, ~3 Minuten)

1. Auf **github.com** ein neues Repository anlegen, z. B. `fernweh` (Public).
2. Alle Dateien aus diesem ZIP hochladen: **Add file → Upload files** →
   `index.html`, `sw.js`, `manifest.webmanifest`, `icon-192.png`, `icon-512.png`
3. Im Repo: **Settings → Pages** → Source: *Deploy from a branch* → Branch `main`, Ordner `/ (root)` → **Save**
4. Nach ~1 Minute ist die App erreichbar unter:
   `https://DEINNAME.github.io/fernweh/`
5. Diese URL in **Chrome auf dem Handy** öffnen → Menü ⋮ → **„App installieren"**
   → Fernweh landet mit eigenem Icon in deiner App-Liste, läuft im Vollbild und auch offline. ✅

## Variante B – Ohne GitHub (Claude-Veröffentlichung)

In der Claude-App die Datei-Vorschau öffnen → Teilen/Veröffentlichen →
den öffentlichen Link in Chrome öffnen → ⋮ → „Zum Startbildschirm hinzufügen".

## Nach der Installation

- **KI-Funktionen:** In der App unter „Reisen" → ⚙ einen Anthropic API-Key
  eintragen (console.anthropic.com). Ohne Key funktioniert alles außer den
  KI-Buttons – die Ziel-Datenbank mit 430+ Orten ist eingebaut.
- **Deine Reisen mitnehmen:** In der Claude-Version ⚙ → Exportieren,
  in der installierten App ⚙ → Text einfügen → Importieren.

## Warum ging die heruntergeladene Datei nicht?

Chrome auf Android kann HTML-Dateien aus dem Download-Ordner (content://…)
oft nicht erneut öffnen – das ist eine Android-Einschränkung, kein Fehler
der App. Über eine echte Web-Adresse (Variante A/B) passiert das nie.
