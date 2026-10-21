# firmenwebseiten.at – Claude-Plugin

Österreichische Firmen auf [firmenwebseiten.at](https://www.firmenwebseiten.at) direkt aus Claude Code suchen und als Inhaber den eigenen Firmeneintrag pflegen (Profil, Kontakt, Standorte, Branchen, Logo, Bilder, Antworten auf Bewertungen, Statistiken).

## Installation (Claude Code)

```bash
claude plugin marketplace add AdSimple-GmbH/firmenwebseiten-claude-plugin
claude plugin install firmenwebseiten@adsimple
```

Das Plugin verbindet den entfernten MCP-Server `https://www.firmenwebseiten.at/api/mcp`. Die Firmensuche funktioniert ohne Anmeldung. Für die Verwaltung eigener Firmen öffnet sich beim ersten Zugriff die Anmeldung bei firmenwebseiten.at; Sie erlauben den Zugriff dort und können ihn jederzeit unter **Profil → Verbundene KI-Assistenten** wieder trennen.

Bewusst nicht möglich: Firmen löschen, Abos abschließen oder kündigen, Kontoeinstellungen ändern. Das erledigen Sie im Dashboard.

## claude.ai und ChatGPT

Derselbe Server funktioniert als benutzerdefinierter Konnektor in claude.ai (Authentifizierung „Bei Bedarf anmelden“) und als MCP-Server in ChatGPT. Details: https://www.firmenwebseiten.at/ki-assistenten

## Kontakt

AdSimple GmbH · https://www.firmenwebseiten.at/kontakt · [Datenschutz](https://www.firmenwebseiten.at/datenschutz)

---

**English:** Claude Code plugin for the Austrian business directory firmenwebseiten.at — search companies without login and manage your own listing after OAuth sign-in. Install with the commands above.
