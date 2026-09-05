# Arduino Stepper Motor Pointer & Position Controller

A precision pointing system driven by a 28BYJ-48 stepper motor, controlled via interactive push-buttons and monitored through an I2C LCD display.

---

## 🇬🇧 English Description

### Overview
This project is a precision pointing mechanism controlled by an Arduino microcontroller. It allows the user to set specific angular shifts using push-buttons, displaying real-time data on an LCD screen and driving a 28BYJ-48 stepper motor via a dedicated driver module.

### Key Features & Hardware Components
* **Microcontroller:** Powered by an Arduino board.
* **Actuator:** 28BYJ-48 stepper motor for precise position control.
* **Driver Module:** ULN2003 driver board used to safely power and control the stepper motor from Arduino.
* **User Input:** Three push-buttons in a pull-down configuration (0 = inactive):
  * *Two buttons* adjust the target angular shift with a minimum resolution of 10 degrees per step.
  * *Central button* triggers the execution of the movement.
* **User Interface:** I2C connected LCD display providing real-time feedback on the configured shift and system status.
* **Power Management:** Utilizes an external power source for the buttons and LCD display to ensure optimal performance and stability of the Arduino board.

---

## 🇮🇹 Descrizione in Italiano

### Panoramica
Un sistema di puntamento di precisione basato su motore passo-passo, gestito da Arduino. Permette di impostare e regolare lo spostamento angolare tramite pulsanti dedicati, visualizzando le informazioni su display LCD e pilotando il motore con un driver apposito.

### Caratteristiche Principali e Componenti
* **Unità di Controllo:** Gestita tramite scheda Arduino.
* **Attuatore:** Motore passo-passo 28BYJ-48 per il controllo del posizionamento angolare.
* **Scheda Driver:** Modulo ULN2003 per il pilotaggio sicuro del motore stepper.
* **Interfaccia di Comando:** Tre pulsanti in configurazione pull-down (0 = non attivo):
  * *Due pulsanti* per regolare lo spostamento con un incremento/decremento minimo di 10 gradi.
  * *Pulsante centrale* per confermare ed eseguire il movimento.
* **Interfaccia Utente:** Display LCD con connessione I2C per mostrare le informazioni sullo spostamento impostato.
* **Gestione Alimentazione:** Alimentazione esterna dedicata per i pulsanti e il display LCD, scelta per alleggerire il carico e permettere ad Arduino di funzionare in condizioni ottimali.

---

## 🔌 Media & Resources / Materiale e Documentazione
* **Schema Elettrico / Schematic:** <img width="1070" height="589" alt="Schema Elettrico" src="https://github.com/user-attachments/assets/af590064-4bb8-4d16-96ce-7c8695e96d39" />
* **Video Dimostrativo / Demo Video:** [Link al video su YouTube]
