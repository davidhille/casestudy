# EventDrive – Klickbarer Prototyp

Klickbarer Prototyp für die Case Study "Ticketshop für das Händlernetz eines Automobilherstellers".

🔗 **Live:** https://davidhille.github.io/casestudy/index.html

## Worum es geht

EventDrive ist eine Plattform, über die ein Automobilhersteller zentrale Events (z. B. Golf-Turniere, Messeauftritte, Fahrerlebnisse) anlegt und sein Händlernetz Tickets dafür reservieren und bestellen lässt. Der Prototyp deckt vier Rollen ab:

- **Event-Manager** (Zentrale): Events anlegen, Kontingente und Phasen steuern
- **Autohaus**: Tickets reservieren, bestellen, Gäste erfassen
- **Zentrale Administration**: Gäste-Compliance prüfen, Daten exportieren, Nutzer verwalten
- **Check-in-Personal**: Tickets am Eingang scannen

Die Rolle lässt sich direkt im Prototyp über den Login-Screen bzw. die Rollenauswahl oben rechts wechseln. Über den Button "Hinweise ein/aus" lässt sich je Screen einblenden, was gezeigt, was vereinfacht und was bewusst weggelassen wurde (inkl. geplanter Tranche).

## Hintergrund

Der Prototyp ist Teil einer dreiteiligen Case Study:

1. Klickbarer Prototyp (dieses Repo)
2. User Stories mit Akzeptanzkriterien
3. Umsetzungsweg auf einer Seite

Die vollständige Dokumentation (Anforderungsanalyse, Prototyp-Beschreibung, User Stories, Umsetzungsweg, Erweiterungsideen) liegt in Confluence, die Backlog-Tickets in Jira.

## Technik

Eine einzelne, selbstständige `index.html` (kein Build-Prozess, keine Abhängigkeiten außer Google Fonts) mit simuliertem Zustand im Browser – es gibt kein echtes Backend, alle Daten werden bei "Demo zurücksetzen" wieder auf den Ausgangsstand gesetzt.

Gehostet über GitHub Pages direkt aus diesem Repository (Branch `main`, Ordner `/`).
