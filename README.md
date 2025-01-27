

  # Setting Up Internet Connection Using LiteBeams and PowerBeams
  <details>
<summary>
Details are here
</summary>
To connect the internet from a landline and extend it using **LiteBeams** and **PowerBeams**, you are essentially creating a wireless point-to-point (P2P) or point-to-multipoint (P2MP) network. This type of setup is often used for long-distance wireless internet connections. Here’s an easy-to-follow guide with the essential knowledge and steps:

---

## **1. Basic Understanding of Equipment**
### **a. LiteBeam and PowerBeam:**
- **LiteBeam:** Used for shorter distances (up to 5 km in ideal conditions). It provides high-speed connections and is easy to set up.
- **PowerBeam:** Offers better performance for longer distances (5–15+ km) with higher throughput and stability.

Both devices use directional antennas to create a focused wireless connection.

### **b. Internet Source:**
- A **modem/router** connected to your landline is your internet source. You’ll connect this to the LiteBeam/PowerBeam.

### **c. Frequency Bands:**
- **2.4 GHz**: Better for longer range and obstacles but slower speeds.
- **5 GHz**: Faster speeds but requires a clear line of sight (LOS).

---

## **2. What You Need**
1. **Modem/Router:** Connected to your landline for internet.
2. **LiteBeam/PowerBeam Units:** Two units (one for transmission and one for reception).
3. **LAN Cables:** To connect devices.
4. **Power-over-Ethernet (PoE) Injectors:** Included with LiteBeam/PowerBeam to power the units.
5. **Mounting Equipment:** Poles or tripods to mount the devices.
6. **Clear Line of Sight (LOS):** Ensure no obstacles like trees or buildings between the units.

---

## **3. Setup Steps**
### **Step 1: Configure LiteBeam/PowerBeam**
1. **Connect to a Computer:**
   - Connect the LiteBeam/PowerBeam to your computer using a LAN cable.
   - Power it up using the PoE injector.

2. **Access Configuration Interface:**
   - Open a web browser and access the device through its default IP address (e.g., `192.168.1.20`).
   - Use the default login credentials (refer to the manual).

3. **Set Up Modes:**
   - **Transmitter (AP mode):** Configure the device connected to the landline router as an **Access Point (AP)**.
   - **Receiver (Station mode):** Configure the remote device as a **Station** or **Client**.

4. **Configure Wireless Settings:**
   - Set frequency (2.4 GHz/5 GHz), channel width, and SSID (network name).
   - Use WPA2 encryption for secure communication.

5. **Test Connection:** Ensure both devices are communicating and aligned.

---

### **Step 2: Mount the Devices**
1. **Position the Devices:**
   - Mount one unit at the internet source location (landline router).
   - Mount the second unit at the remote location where Wi-Fi is needed.

2. **Align the Devices:**
   - Use the built-in alignment tool or signal strength indicator in the configuration interface.
   - Fine-tune the alignment for maximum signal strength.

---

### **Step 3: Connect to the Wi-Fi**
- **Connect Transmitter (AP):** Plug the transmitter unit into your landline router via LAN.
- **Distribute Wi-Fi Locally:**
   - Connect the receiver to a Wi-Fi router or access point at the remote location.
   - Configure the router for wireless distribution.

---

## **4. Additional Tips**
- **Power Supply:** Ensure a stable power supply to all devices.
- **Weather Protection:** Shield the units from extreme weather by using weatherproof enclosures.
- **Regular Maintenance:** Periodically check alignment and clean devices to ensure performance.

---

## **5. Resources to Learn More**
- **Ubiquiti Documentation:** Visit Ubiquiti’s official website for detailed manuals.
- **Online Tutorials:** Search for LiteBeam/PowerBeam setup tutorials on YouTube.
- **Networking Basics:** Learn about IP addresses, subnets, and basic router configurations.

By following this guide and ensuring a clear LOS, you can successfully extend your landline internet connection using LiteBeams and PowerBeams.

</details>

