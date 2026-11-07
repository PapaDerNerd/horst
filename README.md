# Jarvis

**English** | [Deutsch](#deutsch)

![Jarvis main screen](screenshot-chat.png)

Jarvis is a personal AI assistant for Windows with an Iron-Man-style interface. It runs on your own PC with a local language model (Ollama), so your documents, notes and conversations stay on your machine. You talk or type to it, and it answers, looks things up and gets things done.

## Try it: the Standard edition
The **Standard edition** is a complete, free version you can install and use right away. It already does a lot: chat and voice, questions about your own documents, weather, news, timers, notes, calendar and mail overview, web search with sources, reading the screen and more.

1. Download `Jarvis-Standard-Setup.zip` from the [latest release](../../releases/latest).
2. Unzip it and run `setup.bat` (the guide in the package explains the rest).
3. Install [Ollama](https://ollama.com) if you do not have it yet; the setup wizard helps you pick a model.

## What Jarvis can do
- Chat and voice: speak or type, answers can be read aloud (local Piper voice or browser voices).
- Your documents: ask questions about your own files (PDF, Word, Excel, text, scans with OCR) and get answers with the source.
- Everyday helper: weather and rain radar, news, timers, notes, tasks, calendar and mail overview, launching programs, media and volume control.
- Web search with clickable sources.
- Morning briefing and long-term memory (Jarvis can remember facts when you allow it).
- Read the screen: Jarvis can read what is currently shown on your screen (OCR) on request.
- Pro / Pro+: cloud models as an option (Claude, Gemini, OpenAI), image generation (cloud or local ComfyUI), creating and editing Excel, Word and PowerPoint files, uploading files and images.
- Available in German and English. Help, setup wizard, hardware check and a model recommendation list are built in.

![Settings](screenshot-settings.png)

## Editions
- **Standard**: local assistant (Ollama only), free to download here.
- **Pro / Pro+**: additional features. Their update packages are published **encrypted** in the releases and need a key.

## Online update
In Jarvis open Settings > System > Online update via GitHub. The repository `PapaDerNerd/jarvis` is prefilled. Jarvis looks for a newer release once a day, downloads the package for your edition and installs it with a backup of the old version. Pro/Pro+ packages (`*.zip.enc`) are decrypted with your key (Settings > System > Key for Pro / Pro+). The model recommendations (`modelle.json`) are fetched from this repository as validated data only.

## Downloads
See [Releases](../../releases). `Jarvis-Standard-Setup.zip` (full Standard installation) and `Jarvis-Standard-Update.zip` are open; the `.enc` files are encrypted and unreadable without a key.

## Privacy
Jarvis runs locally. Nothing is sent to the cloud unless you switch on a cloud model yourself (Pro/Pro+). Keys are not part of this repository.

---

# Deutsch

![Jarvis Hauptbildschirm](screenshot-start.png)

Jarvis ist ein persönlicher KI-Assistent für Windows im Iron-Man-Stil. Er läuft auf deinem eigenen PC mit einem lokalen Sprachmodell (Ollama), deine Dokumente, Notizen und Gespräche bleiben also auf deinem Rechner. Du sprichst oder schreibst mit ihm, und er antwortet, schlägt nach und erledigt Dinge.

## Zum Ausprobieren: die Standard-Version
Die **Standard-Version** ist eine vollständige, kostenlose Version, die du sofort installieren und nutzen kannst. Sie kann schon viel: Chat und Sprache, Fragen zu eigenen Dokumenten, Wetter, Nachrichten, Timer, Notizen, Kalender- und Mail-Überblick, Websuche mit Quellen, Bildschirm lesen und mehr.

1. Lade `Jarvis-Standard-Setup.zip` aus dem [neuesten Release](../../releases/latest) herunter.
2. Entpacke die ZIP und starte `setup.bat` (die Anleitung im Paket erklärt den Rest).
3. Installiere [Ollama](https://ollama.com), falls noch nicht vorhanden; der Einrichtungsassistent hilft bei der Modellwahl.

## Was Jarvis kann
- Chat und Sprache: sprechen oder schreiben, Antworten auf Wunsch vorgelesen (lokale Piper-Stimme oder Browser-Stimmen).
- Deine Dokumente: Fragen zu eigenen Dateien (PDF, Word, Excel, Text, Scans mit OCR), Antwort mit Quellenangabe.
- Alltagshelfer: Wetter und Regenradar, Nachrichten, Timer, Notizen, Aufgaben, Kalender- und Mail-Überblick, Programme starten, Medien- und Lautstärkesteuerung.
- Websuche mit anklickbaren Quellen.
- Morgen-Überblick und Langzeitgedächtnis (Jarvis merkt sich Fakten, wenn du es erlaubst).
- Bildschirm lesen: Auf Wunsch liest Jarvis, was gerade auf deinem Bildschirm steht (OCR).
- Pro / Pro+: Cloud-Modelle als Option (Claude, Gemini, OpenAI), Bilderstellung (Cloud oder lokal mit ComfyUI), Excel-, Word- und PowerPoint-Dateien erstellen und bearbeiten, Dateien und Bilder hochladen.
- Auf Deutsch und Englisch. Hilfe, Einrichtungsassistent, Hardware-Check und Modellempfehlungen sind eingebaut.

## Editionen
- **Standard**: lokaler Assistent (nur Ollama), hier frei herunterladbar.
- **Pro / Pro+**: zusätzliche Funktionen. Die Update-Pakete liegen in den Releases **verschlüsselt** und brauchen einen Key.

## Online-Update
In Jarvis unter Einstellungen > System > Online-Update über GitHub. Das Repository `PapaDerNerd/jarvis` ist voreingetragen. Jarvis sieht einmal täglich nach einer neueren Version, lädt das Paket deiner Edition herunter und installiert es mit Sicherung der alten Version. Pro/Pro+-Pakete (`*.zip.enc`) werden mit deinem Key entschlüsselt (Einstellungen > System > Key für Pro / Pro+). Die Modellempfehlungen (`modelle.json`) werden aus diesem Repository geholt, nur als geprüfte Daten.

## Downloads
Siehe [Releases](../../releases). `Jarvis-Standard-Setup.zip` (vollständige Standard-Installation) und `Jarvis-Standard-Update.zip` liegen offen; die `.enc`-Dateien sind verschlüsselt und ohne Key nicht lesbar.

## Datenschutz
Jarvis läuft lokal. Nichts geht in die Cloud, solange du nicht selbst ein Cloud-Modell einschaltest (Pro/Pro+). Keys sind nicht Teil dieses Repositorys.
