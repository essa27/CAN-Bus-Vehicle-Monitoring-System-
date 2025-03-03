Acest proiect implementează un sistem de monitorizare a vehiculelor folosind CAN Bus. Sistemul poate citi și afișa date despre viteză, turație motor, temperatură motor și nivel combustibil, comunicând prin protocolul CAN (Controller Area Network).
Funcționalități
 Citire date CAN din rețeaua vehiculului
 Afișare viteză, turație motor, temperatură și nivel combustibil
 Compatibilitate cu OBD-II pentru diagnoză auto
 Conectare la LCD 16x2 sau OLED pentru afișare în bord
 Transmitere date către un server prin Wi-Fi (ESP32)
 
 Asamblare hardware

Se conectează MCP2515 la STM32/Arduino:
VCC → 5V
GND → GND
CS → D10
SCK → D13
MOSI → D11
MISO → D12
Conectează pinii CANH și CANL la rețeaua CAN a vehiculului.

Încărcarea codului în Arduino:
Instalează librăria MCP_CAN în Arduino IDE.
Compilează și încarcă codul pe STM32/Arduino.
Monitorizare date CAN

Conectează un modul USB-CAN Analyzer la laptop pentru a vedea mesajele.
Poți folosi un display LCD/OLED pentru afișarea în timp real.
