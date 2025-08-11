# Wireshark Packet Capture - Task 5


## First Time Boot into Kali Linux
This was my first time booting into **Kali Linux**, and I was a bit confused at first.  
I visited the Kali Linux documentation and then searched in Firefox for "Wireshark in Linux."  

## Objective
Capture live packets and identify basic protocols.

## Tools Used
- Wireshark

```bash 
sudo apt update
sudo apt install wireshark

```
## Steps Performed
1. Captured packets for 1 minute.
2. Filtered traffic for HTTP, DNS, TCP.
3. Identified protocols and noted details.

## Protocols Identified
- HTTP
- DNS
- TCP

## Files
- task5_capture.pcap
- Screenshot of Wireshark analysis
- <img width="1920" height="1080" alt="wireshark" src="https://github.com/user-attachments/assets/45079839-8fd6-4d03-9fe2-98de655545a6" />


Alright — I’ll turn your description into a clean **README.md** you can upload to GitHub along with your `.pcap` file.

Here’s the formatted version:

---

````markdown
# Wireshark Packet Capture - Task 5

## First Time Boot into Kali Linux
This was my first time booting into **Kali Linux**, and I was a bit confused at first.  
I visited the Kali Linux documentation and then searched in Firefox for "Wireshark in Linux."  
It gave me the following installation commands:

```bash
sudo apt update
sudo apt install wireshark
````

I opened a terminal, typed these commands, and successfully installed Wireshark.

---

## Capture Packets

1. Open **Wireshark** → Select your active network interface.
2. Click **Start Capture**.
3. While capturing:

   * Browse some websites
   * Or run:

     ```bash
     ping google.com
     ```
4. Stop after about **1 minute**.

---

## Filter & Analyze

* Apply filters like:

  ```
  http
  dns
  tcp
  ```
* Identify at least **3 protocols**.
* Note details such as:

  * IP addresses
  * Port numbers
  * Packet length

---

## Export the Capture

1. Go to **File → Save As**
2. Choose:

   ```
   task5_capture.pcap
   ```

---

## Files in this Repository

* `README.md` → Instructions & documentation for the task
* `task5_capture.pcap` → Packet capture file


