Erklärung des Projekts - Bitcoin Preis Bot
Was habe ich gemacht?

In dieser Übung sollte ich einen automatisierten Workflow erstellen. Ich habe folgendes Schritt für Schritt umgesetzt:

    Telegram Bot erstellt
        Mit @BotFather einen neuen Bot angelegt
        Bot zum Kanal hinzugefügt und Admin-Rechte gegeben
        Chat-ID des Kanals herausgefunden

    n8n Workflow gebaut
        Schedule Trigger (jede Stunde)
        HTTP Request zu CoinGecko API für Bitcoin Preis
        Edit Fields Node zum Speichern des Preises
        Telegram Node zum Senden der Nachricht auf Deutsch

    Docker Compose
        Zum ersten Mal mit Docker Compose gearbeitet
        n8n als Container gestartet
        Mit docker compose up -d gestartetf

    Probleme die ich hatte
        Chat-ID falsch eingegeben (fehlendes -100)
        Expressions in n8n (Preis formatieren, Zeit Berlin)
        Publish vs Execute verstehen
        Markdown/HTML Probleme beim Senden

Was habe ich gelernt?

    Arbeiten mit APIs
    n8n Nodes und Expressions
    Grundlagen von Docker Compose
    Telegram Bot Integration
    Projekt strukturieren und dokumentieren

Dieses Projekt war eine sehr gute praktische Übung und hat mir viel Spaß gemacht.

Erstellt von: Reza
Datum: 13. Mai 2026