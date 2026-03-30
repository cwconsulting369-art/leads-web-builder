# Leads → Website Builder

KI-gestützter Website Builder der Google Maps Leads aus Airtable automatisch in professionelle Websites konvertiert.

## Features
- 📊 Airtable-Integration (Leads ohne Website automatisch laden)
- 🧠 Memory-System (lernt aus jeder Generierung)
- 🔍 Web Search (Reviews via Google Maps automatisch finden)
- ⬇ Download generierter HTML-Websites
- ✏️ Manueller Modus (URL oder Reviews direkt einfügen)

## Deploy
Dieses Repo ist mit Vercel verbunden. Jeder Push auf `main` triggert automatisch ein neues Deployment.

## Konfiguration
URL-Parameter:
- `?key=sk-ant-...` — Anthropic API Key
- `?at=pat...` — Airtable Personal Access Token (für Memory-Sync zurück zu Airtable)

## Entwicklung
Statische Site — kein Build-Schritt nötig. `public/index.html` ist die gesamte App.
