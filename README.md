# Jarvis

**English** | [Deutsch](#deutsch)

Jarvis is a local AI assistant for Windows with an Iron-Man-style interface: chat, voice, documents, calendar and mail, web search, image generation and more. It runs on your own PC with a local language model (Ollama).

## Editions
- **Standard**: local assistant (Ollama only), free to download here.
- **Pro / Pro+**: additional features (cloud models, file upload and editing, and more). Their update packages are published **encrypted** in the releases and need a key.

## Online update
In Jarvis open Settings > System > Online update via GitHub. The repository `PapaDerNerd/jarvis` is prefilled. Jarvis looks for a newer release once a day, downloads the package for your edition and installs it with a backup of the old version. Pro/Pro+ packages (`*.zip.enc`) are decrypted with your key (Settings > System > Key for Pro / Pro+). The model recommendations (`modelle.json`) are fetched from this repository as validated data only.

## Downloads
See [Releases](../../releases). `Jarvis-Standard-Update.zip` is open; the `.enc` files are encrypted and unreadable without a key.

## Privacy
Jarvis runs locally. Nothing is sent to the cloud unless you switch on a cloud model yourself (Pro/Pro+). Keys are not part of this repository.

---

# Deutsch

Jarvis ist ein lokaler KI-Assistent für Windows im Iron-Man-Stil: Chat, Sprache, Dokumente, Kalender und Mail, Websuche, Bilderstellung und mehr. Er läuft auf deinem eigenen PC mit einem lokalen Sprachmodell (Ollama).

## Editionen
- **Standard**: lokaler Assistent (nur Ollama), hier frei herunterladbar.
- **Pro / Pro+**: zusätzliche Funktionen (Cloud-Modelle, Datei-Upload und Bearbeitung und mehr). Die Update-Pakete liegen in den Releases **verschlüsselt** und brauchen einen Key.

## Online-Update
In Jarvis unter Einstellungen > System > Online-Update über GitHub. Das Repository `PapaDerNerd/jarvis` ist voreingetragen. Jarvis sieht einmal täglich nach einer neueren Version, lädt das Paket deiner Edition herunter und installiert es mit Sicherung der alten Version. Pro/Pro+-Pakete (`*.zip.enc`) werden mit deinem Key entschlüsselt (Einstellungen > System > Key für Pro / Pro+). Die Modellempfehlungen (`modelle.json`) werden aus diesem Repository geholt, nur als geprüfte Daten.

## Downloads
Siehe [Releases](../../releases). `Jarvis-Standard-Update.zip` liegt offen; die `.enc`-Dateien sind verschlüsselt und ohne Key nicht lesbar.

## Datenschutz
Jarvis läuft lokal. Nichts geht in die Cloud, solange du nicht selbst ein Cloud-Modell einschaltest (Pro/Pro+). Keys sind nicht Teil dieses Repositorys.
