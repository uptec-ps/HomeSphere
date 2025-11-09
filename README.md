# HomeSphere: Das Private Server-Kontrollzentrum 🏡

**HomeSphere** ist ein schlankes, benutzerfreundliches Administrations-Betriebssystem, verpackt in einem Docker-Container. Es wurde entwickelt, um die Überwachung und Konfiguration Ihres Ubuntu Heimservers so einfach wie möglich zu machen – ganz ohne komplexe Kommandozeilen. **Ihr gesamtes Heimnetzwerk, zentral und sicher in einer *Sphäre* verwaltet.**

---

## 🚀 Funktionen auf einen Blick

* **Zentrale Übersicht:** Intuitive Weboberfläche zur Überwachung des Serverzustands (CPU, RAM, Speicher).
* **Docker-Integration:** Einfache Verwaltung all Ihrer Docker-Container (Starten, Stoppen, Logs).
* **Netzwerk-Kontrolle:** Einblicke in wichtige Netzwerkeinstellungen und -dienste.
* **Sicher und Lokal:** Entwickelt für den Betrieb im lokalen Netzwerk, alle Daten bleiben bei Ihnen.

---

## 🛠️ Installation (Als Docker-App)

Die Installation von **HomeSphere** ist dank Docker schnell und einfach. Führen Sie diesen Befehl auf Ihrem **Ubuntu Server** aus:

### 1. Persistenten Speicher vorbereiten

Erstellen Sie einen Ordner auf Ihrem Host-System, um Konfigurationsdaten zu speichern.
```bash
mkdir -p /opt/homesphere/config
