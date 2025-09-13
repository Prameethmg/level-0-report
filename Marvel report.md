## TASK 1: 3D PRINTING

3D printing starts with making a design on the computer, usually saved as an STL file. This file is then converted into G-code, which gives step-by-step instructions to the printer for building the object layer by layer. In Fused Deposition Modeling (FDM), plastic filaments like PLA, ABS, PETG, or Nylon are melted and extruded through a nozzle, making it useful for strong and low-cost parts. Stereolithography (SLA) instead uses liquid resin that is hardened with a UV laser, while Digital Light Processing (DLP) works in a similar way but uses a projector to cure the resin. These resins can be standard, tough, flexible, or special ones for jewelry and dental applications. FDM is usually chosen for simple, durable objects, while SLA and DLP are preferred for very smooth and detailed prints. In short, FDM focuses on strength and cost, while SLA and DLP give higher accuracy and finish.

![3D printed chess piece](https://github.com/Prameethmg/markdown/blob/main/6c3d4a86c7e767111de1d5661302fa2c.png?raw=true)


## TASK 2: API

An **API (Application Programming Interface)** is just a way for different computer programs to communicate. Imagine one app needs information that another app has—the API acts as the go-between, taking a request and returning data in an organized format.  

To get a real feel for this, I built a **Random Dog Pic Generator**. The project calls out to the public **Dog API**, which then sends back a URL for a random dog picture. My app then takes that URL and displays the image, showing exactly how an application can use an API to pull in content from an external source.  

### Example Output

Here are two random dog pictures:

![dog1](https://github.com/Prameethmg/markdown/blob/main/dog1.png?raw=true)   
![dog2](https://github.com/Prameethmg/markdown/blob/main/dog2.png?raw=true)

## TASK 3: Working with GitHub

To edit or upgrade someone else's code on **GitHub**, you first create your own personal copy of their entire project by clicking the **"Fork"** button. Think of this like making a photocopy of a book from a library; you can't write in the original, but you're free to mark up your own copy.  

Once you have your **fork**, you can make any changes or upgrades you want in a **separate branch** without affecting the original project at all.  

When you're confident that your changes are a valuable improvement, you send them back to the original project's owner by creating a **Pull Request (PR)**. This acts as a formal proposal, allowing the original author to review your work, provide feedback, and decide if they want to merge your contribution into their official project.  

This entire **"fork and pull request"** process is the foundation of collaboration on GitHub, allowing anyone to safely contribute to open-source software in an organized and respectful way.  


![git](https://github.com/Prameethmg/markdown/blob/main/Screenshot%20(386).png?raw=true)  


## TASK 4: Command Lines on Ubuntu

At first, I was pretty confused about the difference between **Linux** and **Ubuntu**, but the following logic really helped clear things up for me.  

Think of **Linux** as a super powerful car engine; it's the core technology that makes a computer's basic parts work, but you can't really drive just an engine on its own.  

That's where **Ubuntu** comes in. It's the complete, ready-to-drive car built around that engine, adding all the friendly things we actually use—the desktop we see, the icons we click, and the software.  

So, Ubuntu is a popular type of Linux that packages the powerful engine into something we can all easily use.  

### Example Output

![ubuntu](https://github.com/Prameethmg/markdown/blob/main/ubuntu.png?raw=true)


## TASK 5: Create a Portfolio Webpage

I developed this **portfolio website** as a personal project to demonstrate my proficiency in **front-end development**. The site was built entirely from scratch, allowing me to manage the complete technical breakdown from concept to deployment.  

The process began by structuring the content with clean, semantic **HTML**, followed by styling with **CSS** to achieve a visually appealing and fully responsive layout for all devices.  

To create a more engaging and dynamic user experience, I then implemented **JavaScript** to power interactive elements like project galleries, smooth animations, and a functional contact form.  

### Portfolio Link  

[Portfolio Link](https://prameethmg.github.io/portfolio/)


## TASK 6: Writing Resource Article using Markdown


**Markdown** is an easy-to-use markup language that is used with plain text to add formatting elements (such as headings, bulleted lists, and URLs) without the need for a formal text editor or HTML tags.  

Markdown is **device agnostic** and displays the writing format consistently across different device types.  

### Key Features of Markdown
- Simple syntax, easy to learn  
- Supports **headings**, **bold**, and *italic* text  
- Can create **lists** (ordered and unordered)  
- Can embed **links** and **images**  
- Works across platforms and devices  

### Example Link
![](https://github.com/Prameethmg/markdown-2/blob/main/Screenshot%20(388).png?raw=true)



## TASK 7: Tinkercad  

Within Tinkercad's **Circuits** workspace, I connected an ultrasonic sensor's **VCC** and **GND** pins to the Arduino's **5V** and **GND**, then connected the **Trig** and **Echo** pins to digital pins.  

I then coded the Arduino to send out a sound wave via the **Trig** pin and measure the duration it took for the echo to return to the **Echo** pin, which allowed me to calculate the distance to a virtual object.  

![](https://github.com/Prameethmg/markdown-2/blob/main/ufbf.png?raw=true)


## TASK 8: Speed Control of DC Motor  

The offline phase of the project involved constructing the physical prototype based on the validated Tinkercad simulation. The circuit was assembled using an **Arduino UNO** microcontroller, an **L298N H-bridge motor driver**, and a **BO motor**, with wiring that mirrored the digital schematic.  

An external power source was connected to the L298N to adequately power the motor, a step crucial for preventing damage to the Arduino. The pre-tested code was then uploaded to the Arduino, commanding the L298N driver to control the motor's speed using **Pulse Width Modulation (PWM)** signals and its direction by toggling digital pins.  

The physical motor's performance ramping speed, stopping, and reversing identically matched the behavior observed in the simulation, confirming the design's functionality.  


![](https://github.com/Prameethmg/markdown-2/blob/main/dc%20mootor%202.jpg?raw=true)
![](https://github.com/Prameethmg/markdown-2/blob/main/motor%2034.jpg?raw=true)



## TASK 9: LED Toggle Using ESP32  

The core of this task involved uploading an Arduino sketch that connects the **ESP32** to a local Wi-Fi network and starts a server. This server listens for **HTTP GET** requests generated by a web browser.  

When a request like **/26/on** or **/27/off** is received, the code parses the URL and uses `digitalWrite()` to change the state of the corresponding LED.  

After uploading the code and obtaining the ESP32's **IP address** from the Serial Monitor, I could access the control interface from any device on the same network, providing a practical introduction to building functional **IoT applications**.  


![](https://github.com/Prameethmg/markdown-2/blob/main/led%20toggle%2045.jpg?raw=true)
![](https://github.com/Prameethmg/markdown-2/blob/main/led%20toggle%2046.jpg?raw=true)


## TASK 10: Soldering Prerequisites  

Soldering is done by using a **hot iron** to heat the connection point where the component lead and circuit board meet. You then apply **solder** to the heated joint; as it melts, the **flux core** inside activates, chemically cleaning the surfaces and allowing the molten solder to flow smoothly.  

Removing the iron lets the solder cool and solidify, creating a strong and conductive **electrical bond**.  

![](https://github.com/Prameethmg/markdown-2/blob/main/soldering.jpg?raw=true)


## TASK 11: 555 Astable Multivibrator  

To complete this task, I designed and tested a **555 timer-based astable multivibrator** with a specific **60% duty cycle**.  

First, I used the duty cycle formula:  

\[
D = \frac{R1 + 2R2}{R1 + R2}
\]  

to calculate that the required resistor ratio was **R2 = 2R1**. Based on this, I selected standard component values of **R1 = 10 kΩ**, **R2 = 20 kΩ**, and a timing capacitor **C = 1 µF**.  

After calculating the component values, I rigged up the complete circuit on a **breadboard**, ensuring the 555 timer's pins were connected correctly to the resistors, capacitor, and power supply.  

Finally, I connected the **Digital Storage Oscilloscope (DSO)** probe to the output pin (**pin 3**) of the 555 IC. On the DSO's screen, I observed a continuous **square wave** and used the built-in measurement tools to verify that the waveform's **high time was approximately 60%** of the total period, confirming the circuit was functioning exactly as designed.  


![](https://github.com/Prameethmg/markdown-2/blob/main/555.jpg?raw=true)
![](https://github.com/Prameethmg/markdown-2/blob/main/duty%20cycle.jpg?raw=true)


## TASK 12: Karnaugh Maps and Deriving the Logic Circuit  

The objective was to design a **custom alarm circuit** with two inputs: a **door sensor (D)** and a **key switch (K)**. The specific logic for this alarm is that it activates only when the **door is open (D = 1)** and the **key is not in use (K = 0)**, meaning the key acts as a manual override to safely keep the door open.  

---

### Case Analysis  

- **Case 1: Door Closed (D=0), Key Not Used (K=0)**  
  - The system is completely inactive.  
  - No threat detected.  
  - **Alarm remains off (A=0).**  
  - This is a default safe state.  

- **Case 2: Door Closed (D=0), Key Used (K=1)**  
  - The key being used means the system is "armed" or being controlled.  
  - However, the door is still closed.  
  - No breach, so the **alarm remains off (A=0).**  
  - This could be the state when someone is inside with the door secured.  

- **Case 3: Door Open (D=1), Key Not Used (K=0)**  
  - This is the **critical trigger condition.**  
  - The door has been opened without the "safe" key being engaged.  
  - A potential intrusion is detected.  
  - **The alarm sounds (A=1).**  

- **Case 4: Door Open (D=1), Key Used (K=1)**  
  - The door is open, but the key is being used.  
  - This signifies an authorized action (e.g., someone intentionally holding the door open with the key).  
  - The alarm is suppressed due to the key override.  
  - **Alarm remains off (A=0).**  

![](https://github.com/Prameethmg/markdown-2/blob/main/Gemini_Generated_Image_99ulro99ulro99ul.png?raw=true)
![](https://github.com/Prameethmg/markdown-2/blob/main/kmap.png?raw=true)
![](https://github.com/Prameethmg/markdown-2/blob/main/equation.png?raw=true)

## TASK 13: Active Participation  

I had participated at **Impetus** this year in **Silico Hack** and **Think Tank**.  

![](https://github.com/Prameethmg/markdown-2/blob/main/think%20tank.png?raw=true)
![](https://github.com/Prameethmg/markdown-2/blob/main/silico%20hack.png?raw=true)

## TASK 14: Datasheets Report Writing  
### Report on L293D Motor Driver IC  

---

### Introduction  
The **L293D** is a dual-channel **H-bridge motor driver IC** designed to control two DC motors independently or one stepper motor. Each channel functions as a full H-bridge, allowing motors to rotate forward, backward, or stop.  

The IC can also drive other inductive loads such as solenoids, relays, and actuators. Because of its versatility, the L293D is widely used in **robotics, embedded systems, and automation projects**.  

---

### Key Features  
- Dual H-bridge (2 channels)  
- Motor voltage supply: **4.5V – 36V**  
- Logic supply voltage: **5V**  
- Continuous current: **600 mA per channel**  
- Peak current: **1.2 A per channel**  
- Internal kickback protection diodes  
- Separate logic and motor supply pins  

---

### Pin Configuration  

**Diagram Description:**  
The IC is a **16-pin DIP package**.  

- Pins **1 & 9 (Enable pins):** Used to enable/disable each H-bridge.  
- Pins **2, 7, 10, 15 (Input pins):** Logic signals from microcontroller.  
- Pins **3, 6, 11, 14 (Output pins):** Connected to motor terminals.  
- Pins **4, 5, 12, 13 (Ground pins):** Must be connected to GND.  
- Pin **8 (Vcc2):** Motor supply voltage (4.5V–36V).  
- Pin **16 (Vcc1):** Logic supply voltage (5V).  

*(Draw the 16-pin layout with arrows showing inputs, outputs, and enable pins.)*  

---

### Internal Protection and Current Handling  
The L293D integrates **internal clamp diodes (kickback diodes)** to protect against back-EMF generated when motors are suddenly switched OFF.  

- Continuous current: **600 mA per channel**  
- Peak current: **1.2 A (short duration)**  
- Suitable for **small to medium DC motors**  


![](https://how2electronics.com/wp-content/uploads/2022/08/L293D-Motor-Driver-IC.jpg)
---

### H-Bridge Concept  

**Diagram Description:**  
- Draw an "H" circuit with 4 switches (**Q1, Q2, Q3, Q4**).  
- Place the motor as the horizontal bar of the H.  
- Show arrows of current direction for forward and reverse cases.  

**Explanation:**  
- **Forward:** Q1 & Q4 ON → current flows left to right.  
- **Reverse:** Q2 & Q3 ON → current flows right to left.  
- **Stop:** All OFF → motor idle.  
- **Brake:** Q1 & Q3 ON or Q2 & Q4 ON → motor stops instantly.  

The **H-bridge** makes the L293D capable of **bidirectional motor control**.  

![](https://www.hackatronic.com/wp-content/uploads/2025/01/H-Bridge-Motor-Driver-Circuit-Diagram-.webp)
---

### PWM (Pulse Width Modulation) for Speed Control  

**Diagram Description:**  
- Draw a PWM waveform showing **HIGH (ON)** and **LOW (OFF)** pulses.  
- Show that duty cycle (**ON time ÷ Total time**) changes effective voltage.  

**Explanation:**  
- The L293D uses **PWM signals** applied to Enable pins (**EN1, EN2**) to control speed.  
- **High Duty Cycle:** More ON time → motor spins faster.  
- **Low Duty Cycle:** Less ON time → motor spins slower.  
- Frequency: Typically a few kHz, ensuring **smooth motion without jerks**.  

---

### Applications  
- Robotics (wheel drive, robotic arms)  
- Stepper motor control in **CNC and 3D printers**  
- Conveyor belts and mechatronics systems  
- Home automation (door locks, actuators)  
- **Arduino/Raspberry Pi DIY projects**  

![](https://circuitdigest.com/sites/default/files/projectimage_tut/Pulse-Width-Modulation.jpg)
---

### Conclusion  
The **L293D motor driver IC** is a **reliable and cost-effective solution** for controlling small to medium DC motors and stepper motors. With its built-in H-bridge configuration, **PWM compatibility**, and **internal protection diodes**, it provides both speed and direction control.  

Its wide voltage range and current handling capacity make it one of the **most widely used motor drivers** in **educational, industrial, and embedded applications**.  


## Task 15: Introduction to VR  

**Virtual Reality (VR)** is a technology that completely immerses you in a simulated, digital environment using a headset that blocks out your real-world surroundings.  

In contrast, **Augmented Reality (AR)** overlays digital information, such as images and text, onto your view of the real world, typically through a smartphone or smart glasses.  

Essentially, **VR aims to replace your reality**, while **AR seeks to enhance it**.  

I also got a chance to **explore VR at Marvel**, which provided a hands-on experience of immersive digital environments.  

![](https://github.com/Prameethmg/markdown-2/blob/main/vr.jpg?raw=true)














