# Pwnagotchi
Pwnagotchi is an A2C-based “AI” powered by bettercap and running on a Raspberry Pi Zero W that learns from its surrounding WiFi environment in order to maximize the crackable WPA key material it captures (either through passive sniffing or by performing deauthentication and association attacks). This material is collected on disk as PCAP files containing any form of handshake supported by hashcat, including full and half WPA handshakes as well as PMKIDs.

<img src="https://github.com/0V-N/Seasides2025/blob/main/Images/pwnagotchi1.jpg" alt=" Deauther mini" style="width: 300px; float: left; margin-right: 20px;">

## Key Features:

AI-Powered Learning: Pwnagotchi uses a neural network to improve its handshaking capture efficiency as it learns from the environment.

Compact & Portable: Powered by the Raspberry Pi Zero W, it is small, lightweight, and designed for easy portability.

Hacker-Friendly Interface: The device features an interactive OLED screen that displays the progress and stats, including captured handshakes, battery status, and more.

WiFi Auditing: Pwnagotchi can capture WPA handshakes, making it useful for WiFi password cracking when combined with proper tools.

Customizable: Users can tweak various settings, such as the Pwnagotchi’s behavior and personality, to suit their needs.

Battery Efficiency: Designed to be low power, it maximizes battery life for long-term operation, making it ideal for field use.

Community Driven: Pwnagotchi has an active community that continually improves its software and offers tips for maximizing its effectiveness

## How Pwnagotchi Works
Pwnagotchi operates as an AI-powered device designed to capture WiFi handshakes and perform other WiFi security tasks, including passive monitoring and WiFi spoofing. Below is a step-by-step overview of how it functions:

<img src="https://github.com/0V-N/Seasides2025/blob/main/Images/pwnagotchi2.jpg" alt=" Deauther mini" style="width: 300px; float: left; margin-right: 20px;">

### Power On:
When you power on the Pwnagotchi, it starts booting up its Raspberry Pi Zero W, which runs custom software based on the Pwnagotchi OS. The device is powered by a small battery, optimized for long-term operation.

### Scanning for Networks:
Pwnagotchi continuously scans the environment for nearby WiFi networks. It passively listens to wireless traffic to identify WPA/WPA2 networks. This does not involve actively connecting to networks, so it stays undetected by users.

### AI-Powered Learning:
The core feature of Pwnagotchi is its use of artificial intelligence. It employs a neural network to learn from its surroundings and improve its performance over time. As it encounters different networks, it adapts its behavior to optimize its efficiency in capturing WPA handshakes. The more it learns, the better it becomes at targeting networks and collecting data.

### Capturing Handshakes:
Once a suitable WPA handshake is detected, Pwnagotchi automatically captures it. A WPA handshake is a key exchange between a WiFi router and a client (such as a phone or laptop), and it's a critical piece of information used in WiFi password cracking.

### Displaying Information:
Pwnagotchi displays its status on an OLED screen. This includes information like the number of captured handshakes, battery status, the device's current "mood" (based on its AI progress), and other relevant statistics. The OLED screen serves as a way to interact with the device without the need for a computer or external interface.

### Interaction & Customization:
Users can interact with Pwnagotchi via buttons or through the web interface (accessible through its IP address). You can adjust settings like how aggressively it searches for networks or how it reacts to new environments. Additionally, users can change the device's personality (affecting the mood displayed on the screen), or modify its operational parameters.

### WiFi Spoofing & Packet Monitoring:
In addition to passive capturing, Pwnagotchi can also perform WiFi spoofing. It can create fake networks to trick devices into attempting to connect, which can be used for testing or other security purposes. It also supports packet monitoring, which helps detect and analyze the traffic between devices on the network.

### Data Processing & Cracking:
While Pwnagotchi itself doesn’t crack passwords directly, it collects and stores WPA handshakes. These handshakes can later be used in conjunction with tools like Hashcat or Aircrack-ng for password cracking, helping assess the strength of WiFi network security.

### Continuous Operation:
As Pwnagotchi moves around (or as it remains in an environment), it continually learns and refines its ability to capture more handshakes. It uses machine learning techniques to optimize the success rate, enhancing the device's overall effectiveness over time.

By combining AI, machine learning, and WiFi security tools, Pwnagotchi is a powerful, portable, and self-improving device for WiFi auditing and penetration testing.

## Pwnagotchi Personality
One of the unique and charming features of Pwnagotchi is its personality system, which makes it feel like more than just a security tool. The device doesn’t just perform WiFi tasks—it expresses emotions, reacts to its environment, and builds a “relationship” with its user. This personality system is both functional and entertaining, turning Pwnagotchi into an interactive companion.

<img src="https://github.com/0V-N/Seasides2025/blob/main/Images/pwnagotchi3" alt=" Deauther mini" style="width: 300px; float: left; margin-right: 20px;">

## Pwnagotchi Hardware

Pwnagotchi is powered by the Raspberry Pi Zero module, and other Raspberry Pi models (such as the Pi 3, Pi 4, Pi 5, and Pi Zero W2) are also supported. It displays details on an e-ink paper display, and the image is flashed onto an SD card.

<div align="center">
  <img src="https://github.com/0V-N/Seasides2025/blob/main/Images/pwnhard1.jpg" alt="Hardware" width="600">
</div>


<div align="center">
  <img src="https://github.com/0V-N/Seasides2025/blob/main/Images/pwnhard2.jpg" alt=" Hardware " width="600">
</div>


<div align="center">
  <img src="https://github.com/0V-N/Seasides2025/blob/main/Images/pwnhard3.jpg" alt="Hardware" width="600">
</div>

### For more details visit 

 -> https://pwnagotchi.ai/
 
 -> https://pwnagotchi.org/
