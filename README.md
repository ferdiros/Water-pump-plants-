# 🌱 Water Pump Plants – Raspberry Pi Pico

Un progetto semplice ed efficace per mantenere le tue piante sempre innaffiate, anche quando non sei a casa.  
Basato su **Raspberry Pi Pico**, può funzionare sia **con sensori di umidità del terreno** che **senza sensori**, grazie a una logica di temporizzazione.
Per rendere il tutto più complesso ma anche più divertente ho anche implementato un'interfaccia grafica con uno schermo TFT 1,8'' ST7735

---

## 🚀 Funzionalità
- Innaffiatura automatica ogni **8 ore** per **10 secondi** (modalità senza sensori).
- Possibilità di abilitare/disabilitare manualmente tramite pulsante **on/off**.
- Versione con **sensori di umidità capacitiva** per irrigazione più intelligente.
- Schemi elettrici inclusi:
  - ✔️ Con sensori di umidità
  - ✔️ Senza sensori
  - ✔️ Con schermo TFT 1,8" ST7735
---

## 🧩 Componenti necessari
- 1 × Raspberry Pi Pico (o altra development board compatibile)  
- 1 × Breadboard  
- 1 × Relè a 4 canali  
- 4 × Sensori capacitivi di umidità del suolo  
- 4 × Mini pompe ad acqua 5V  
- Tubi per irrigazione  
- 1 × Contenitore batterie
- 1 x schermo TFT 1,8" ST7735 [ opzionale ]

---

> ℹ️ Gli schemi elettrici completi sono disponibili nella cartella `schematics/`.

---

## 📂 Contenuto del repository
- `schematics/` → schemi elettrici (con e senza sensori)  
- `code/` → codice sorgente per Raspberry Pi Pico  
- `docs/` → documentazione aggiuntiva  

---

## ▶️ Come iniziare
1. Collega tutti i componenti seguendo lo schema.  
2. Carica il codice sul Raspberry Pi Pico.  
3. Testa l’impianto con una singola pompa.  
4. Estendi il sistema fino a 4 pompe/sensori.  

---

## 🛠️ Possibili miglioramenti
- Aggiungere un’interfaccia web/app per controllare da remoto.  
- Regolare la durata e la frequenza di irrigazione tramite parametri configurabili.  
- Integrazione con sensori aggiuntivi (es. temperatura, luminosità).  

---

## 📜 Licenza
Questo progetto è distribuito sotto licenza **MIT**.  
Puoi usarlo, modificarlo e condividerlo liberamente.  

---

💧 Buona irrigazione automatica! 🪴
