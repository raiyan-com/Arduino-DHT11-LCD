# Arduino DHT11 Temperature and Humidity LCD Display

I built this project to monitor temperature and humidity in real time using a **DHT11 sensor** and a **16x2 LCD display** with an Arduino Uno R4.

---

🎮 **How It Works**  
- The **DHT11 sensor** measures temperature (°C) and humidity (%).  
- The **LCD screen** shows live readings:  
  - First line: Humidity  
  - Second line: Temperature  
- If the sensor fails, the LCD shows **"Sensor error"**.  
- Readings update every 2 seconds.  

---

✨ **What I Learned**  
Through this project, I practiced:  
- Reading data from a DHT11 sensor  
- Displaying values on a 16x2 LCD using the LiquidCrystal library  
- Handling errors gracefully  
- Combining input sensors and output displays in Arduino  

---

🛠️ **Components**  
- 1 × Arduino Uno R4  
- 1 × DHT11 Temperature & Humidity Sensor  
- 1 × 16x2 LCD Display  
- Jumper wires  
- Breadboard  

---

🔌 **Pin Connections**

| Component | Arduino Pin |
|-----------|-------------|
| DHT11 Data | 9 |
| LCD RS     | 7 |
| LCD E      | 6 |
| LCD D4     | 5 |
| LCD D5     | 4 |
| LCD D6     | 3 |
| LCD D7     | 2 |

---

▶️ **How to Run**  
1. Connect the DHT11 sensor and LCD to the Arduino according to the table above.  
2. Upload the `DHT11_LCD.ino` sketch to your Arduino Uno R4.  
3. Power the Arduino.  
4. Watch the LCD display live humidity and temperature readings every 2 seconds.  
5. If the sensor fails, the LCD will display **"Sensor error"**.  

---

💡 **Tip:**  
You can expand this project by adding **buzzer alerts** or **LED indicators** for high temperature or humidity.
