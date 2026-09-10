# 🌐 Progetto GPO — Interactive 3D Web Environment

Ambiente web interattivo tridimensionale esplorabile, realizzato con Three.js e Cannon.js, completo di simulazione fisica in tempo reale e gestione dinamica di veicoli.

---

## 🛠️ Tech Stack

* **Rendering 3D:** Three.js / WebGL.
* **Engine Fisico:** Cannon.js (Simulazione di gravità, attrito e collisioni rigid-body).
* **Frontend:** JavaScript (ES6+), HTML5, CSS3.
* **Build Tool & Dev Server:** Vite.
* **Controllo Versione:** Git / GitHub.

---

## 🎯 Funzionalità Principali

* 🚘 **Simulazione Veicolo & Fisica:** Controllo guidabile di un veicolo integrato con il motore fisico Cannon.js (gestione sospensioni, attrito e peso).
* 💡 **Illuminazione & Ombre Dinamiche:** Rendering di luci ambientali e direzionali con calcolo delle ombre in tempo reale.
* 🎥 **Telecamera & Controlli:** Gestione fluida della telecamera e interazione con le entità della scena.
* ⚡ **Performance con Vite:** Bundle rapido e Hot Module Replacement (HMR) per un ambiente di sviluppo ad alte prestazioni.

---

## 📦 Installazione e Avvio Locale

### Prerequisiti
* [Node.js](https://nodejs.org/) (versione 16.x o superiore) e `npm` installati sulla macchina.

### 1. Clonare la repository
```bash
git clone [https://github.com/Mcarollo-SYS/Progetto-GPO.git](https://github.com/Mcarollo-SYS/Progetto-GPO.git)
cd Progetto-GPO

npm install
npm install -D vite

npm run dev
