# sleep-detector-project

🔌 Components Used

Arduino UNO

Eye Blink Sensor (with glass)

5V Relay Module

Gear Motor

Buzzer

Jumper wires

🔗 Pin Connections
👁 Eye Blink Sensor
Sensor Pin	Arduino Pin
VCC	5V
GND	GND
OUT	D2
🔔 Buzzer
Buzzer Pin	Arduino Pin
+	D3
–	GND
🔁 Relay Module
Relay Pin	Arduino Pin
VCC	5V
GND	GND
IN	D4
⚙ Gear Motor (via Relay)

COM → External motor supply +

NO → Gear motor +

Gear motor – → External supply –

⚠️ Important:
Do NOT connect motor directly to Arduino.
