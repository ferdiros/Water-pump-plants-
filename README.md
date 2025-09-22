# 🌱 Water Pump Plants – Raspberry Pi Pico

Un progetto semplice ed efficace per mantenere le tue piante sempre innaffiate, anche quando non sei a casa.  
Basato su **Raspberry Pi Pico**, può funzionare sia **con sensori di umidità del terreno** che **senza sensori**, grazie a una logica di temporizzazione.  
Include anche un'interfaccia grafica con uno schermo TFT 1,8'' ST7735 per visualizzare lo stato del sistema.

---

## 🚀 Funzionalità principali
- Innaffiatura automatica ogni **8 ore** per **10 secondi** (modalità senza sensori)  
- Abilitazione/disabilitazione manuale tramite pulsante **on/off**  
- Interfaccia grafica a display con informazioni sullo stato della pompa e countdown  
- Modalità con **sensori di umidità capacitiva** per irrigazione intelligente  
- Schemi elettrici disponibili:
  - ✔️ Con sensori di umidità  
  - ✔️ Senza sensori  
  - ✔️ Con display TFT 1,8" ST7735  

---

## 🧩 Componenti necessari
- 1 × Raspberry Pi Pico (o altra scheda compatibile)  
- 1 × Breadboard  
- 1 × Relè a 4 canali  
- 4 × Sensori capacitivi di umidità del terreno  
- 4 × Mini pompe ad acqua 5V  
- Tubi per irrigazione  
- 1 × Contenitore batterie  
- 1 × Schermo TFT 1,8" ST7735 (opzionale)  

---

## 📂 Contenuto del repository
- `schematics/` → schemi elettrici (con e senza sensori)  
- `code/` → codice sorgente per Raspberry Pi Pico  
- `docs/` → documentazione aggiuntiva  

---

## ▶️ Come iniziare
1. Collega tutti i componenti seguendo lo schema elettrico  
2. Carica il codice sul Raspberry Pi Pico  
3. Testa il sistema con una singola pompa  
4. Estendi il sistema fino a 4 pompe/sensori  

---

## 🛠️ Possibili miglioramenti
- Aggiungere un’interfaccia web/app per controllare il sistema da remoto  
- Regolare la durata e la frequenza di irrigazione tramite parametri configurabili  
- Integrare ulteriori sensori (es. temperatura, luminosità)  
- Visualizzare i dati dei sensori direttamente sul display TFT  

---

## 📜 Licenza
Distribuito sotto licenza **MIT**: puoi usare, modificare e condividere liberamente il progetto  

---

💧 Buona irrigazione automatica! 🪴  

---

# 🌱 Water Pump Plants – Raspberry Pi Pico (English Version)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
[![Platform: Raspberry Pi Pico](https://img.shields.io/badge/Platform-Raspberry_Pi_Pico-blue.svg)](https://www.raspberrypi.com/products/raspberry-pi-pico/)

A simple and efficient project to keep your plants watered automatically, even when you’re not at home.  
Based on the **Raspberry Pi Pico**, it can work **with soil moisture sensors** or **without sensors**, using a timed irrigation logic.  
Includes a graphical interface with a 1.8’’ TFT ST7735 display to show system status.

---

## 🚀 Key Features
- Automatic irrigation every **8 hours** for **10 seconds** (sensor-less mode)  
- Manual on/off control via push button  
- Graphical interface showing pump status and countdown  
- Option with **capacitive soil moisture sensors** for smarter irrigation  
- Electrical schematics available:
  - ✔️ With soil moisture sensors  
  - ✔️ Without sensors  
  - ✔️ With 1.8" TFT ST7735 display  

---

## 🧩 Required Components
- 1 × Raspberry Pi Pico (or compatible board)  
- 1 × Breadboard  
- 1 × 4-channel relay  
- 4 × Capacitive soil moisture sensors  
- 4 × 5V mini water pumps  
- Irrigation tubes  
- 1 × Battery pack  
- 1 × 1.8" TFT ST7735 display (optional)  

---

## 📂 Repository Structure
- `schematics/` → electrical schematics (with and without sensors)  
- `code/` → source code for Raspberry Pi Pico  
- `docs/` → additional documentation  

---

## ▶️ Getting Started
1. Connect all components according to the schematics  
2. Upload the code to the Raspberry Pi Pico  
3. Test the system with a single pump  
4. Expand the setup up to 4 pumps/sensors  

---

## 🛠️ Possible Improvements
- Add a web/app interface for remote control  
- Make irrigation frequency and duration configurable  
- Integrate additional sensors (e.g., temperature, light)  
- Display sensor data on the TFT display  

---

## 📜 License
Distributed under **MIT License**: free to use, modify, and share  

---

💧 Happy automatic watering! 🪴
