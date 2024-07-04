# Android_Home_Automation_Arduino
Arduino-Based Home Automation Controlled by Android



This repository contains the code and resources for building a do-it-yourself home automation system controlled through an Android application. Take control of your home from your smartphone or tablet with features like:

* **Remote Control:** Turn on/off lights, fans, and other appliances directly from your Android app.
* **Easy Setup:** The Arduino platform and visual programming with MIT App Inventor make this project accessible for beginners.
* **Open-source Design:** Explore, modify, and extend the functionalities to suit your specific needs. (Consider adding a note if your code is licensed under a specific license)

**Hardware Components**

* Arduino Nano
* HC-05 Bluetooth Module
* 4-Channel 5V Relay Module
* Jumper Wires (Male-to-Female, Male-to-Male)
* Light Bulb Holders (x2)
* 220V LED Bulbs (x2)
* AC Fan (220V)
* 5V 2Amp Power Adapter
* Breadboard (optional for prototyping)

**Software**

* Arduino IDE
* MIT App Inventor (for Android app development)

**Getting Started**

1. **Review the Hardware Schematics:**  The schematics detail how to connect all the components. (Consider adding the schematics as a file in the repository)
2. **Assemble the Hardware:**  Build the circuit by following the schematics. You can use a breadboard for prototyping or create a permanent layout on a non-conductive surface. 
3. **Install the Arduino Code:**  Upload the provided Arduino code to your Arduino Nano using the Arduino IDE.
4. **Develop the Android App (Optional):**  This repository provides a basic outline for the app functionality. You can use MIT App Inventor to create a custom app with buttons or sliders to control the appliances. Refer to MIT App Inventor tutorials for app development guidance.
5. **Connect the App and Arduino:**  The Android app should communicate with the Arduino via Bluetooth. The code sets up the Bluetooth communication. Pair the Bluetooth module with your Android device.

**Explanation of the Arduino Code:**

The Arduino code utilizes the EEPROM library to maintain the state (on/off) of the appliances even after power cycles. It also uses the SoftwareSerial library to establish serial communication with the Bluetooth module (HC-05). The code continuously reads data from the Bluetooth connection, interprets characters (A-E) corresponding to specific appliances and power state, and controls the relays accordingly.

**Further Exploration:**

This project serves as a foundation for building a more advanced home automation system. You can explore features like:

*  Adding more appliances and functionalities to the app and code.
*  Implementing voice control using voice recognition libraries in the app.
*  Integrating sensors (e.g., temperature, motion) for automated control based on environmental conditions.

**Community**

We welcome contributions and improvements to this open-source project! Feel free to share your ideas, bug fixes, or new functionalities through pull requests.

**License**

(If your code has a specific license)

This project is licensed under the [License Name](link to license).

**Note:**

* Replace the bracketed placeholders with specific details about your project, such as a link to the schematics file. 
* Consider adding comments within the Arduino code to explain specific functionalities.
