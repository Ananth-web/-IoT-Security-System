# -IoT-Security-System:

COMPANY: CODTECH IT SOLUTION

NAME:A.ANANTH

INTERN ID: CT04DH1564

DOMAIN:Internet Of Things

DURATION:4 WEEKS

MENTOR:Neela Santhosh

DESCRIPTION:

Task 3: IoT Security System

Objective: Build a basic IoT-based security system that detects motion using a PIR sensor and triggers an alert (LED/Buzzer), simulating a home or room intrusion detection system.

We’ll use:

PIR sensor → To detect motion

LED/Buzzer → To indicate alert

Serial Monitor → To simulate alert messages
All on Wokwi (Arduino UNO)



---

🔧 Step-by-Step Instructions


---

✅ Step 1: Open Wokwi

Go to https://wokwi.com

Click "New Project"

Select Arduino UNO



---

✅ Step 2: Add Components

Click the pink "+" button, and add:

1 x Arduino UNO

1 x PIR Motion Sensor

1 x LED (for alert)

1 x 220Ω resistor

Jumper wires



---

✅ Step 3: Wiring Diagram

Component	Arduino Pin	Notes

PIR VCC	5V	Power supply
PIR GND	GND	Ground
PIR OUT	Pin 2	Motion detection signal
LED + (Anode)	Pin 13	Via 220Ω resistor
LED – (Cathode)	GND	Connect directly

<img width="1919" height="903" alt="Image" src="https://github.com/user-attachments/assets/279669d0-64ed-425f-be07-7be3d3ccc3ad" />
