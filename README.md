![Kazam_screenshot_00007](https://github.com/user-attachments/assets/5e1dfb3c-df23-47f2-b42b-d009dc91be91)
![Kazam_screenshot_00005](https://github.com/user-attachments/assets/99a635b4-b7bc-414d-95fb-2e2e693a38db)

# DDoS Attack Tool

This is a **DDoS Attack Tool** built with Python and **Tkinter** that allows users to choose from multiple attack methods and configure parameters for the attack. It supports **SYN Flood**, **UDP Flood**, **ICMP Flood**, and **HTTP Flood** methods and allows the user to specify attack duration and the number of threads to use.

### Key Features:
- Select a website URL to target.
- Choose from four different attack methods:  
  - **SYN Flood**
  - **UDP Flood**
  - **ICMP Flood**
  - **HTTP Flood**
- Configure the number of threads to use for the attack.
- Set the attack duration (in seconds).
- Start and stop the attack using simple buttons.

---

## Installation Instructions

### Step 1: Install Dependencies

The tool uses two key dependencies: **hping3** and **slowhttptest**. Use the following commands to install them:

#### **Install `hping3`** (for SYN, UDP, and ICMP Flood):
```bash
sudo apt-get install hping3
```

#### **Install `slowhttptest`** (for HTTP Flood):
```bash
sudo apt-get install slowhttptest
```

---

### Step 2: Run the Tool

Once dependencies are installed, run the tool by using the following command:

```bash
python3 dox.py
```

This will open the GUI where you can:
- Enter the website URL.
- Select the attack method.
- Specify the number of threads and attack duration.
- Start and stop the attack.

---

## How Powerful is This Tool?

The **DDoS Attack Tool** is capable of performing **powerful distributed denial-of-service (DDoS)** attacks using multiple attack vectors:

- **SYN Flood**: Overwhelms the target server by sending a large number of SYN requests.
- **UDP Flood**: Sends a flood of UDP packets, overwhelming the target server's resources.
- **ICMP Flood**: Also known as a "ping flood," it floods the target with ICMP Echo Requests.
- **HTTP Flood**: Simulates real user traffic to overwhelm web servers, potentially causing service denial.

**WARNING**:  
This tool should only be used for educational purposes and on systems or websites that you own or have explicit permission to test. Unauthorized use may violate laws and ethical guidelines. Always ensure you are acting responsibly.

---



https://github.com/user-attachments/assets/a3a4b7b0-9d48-4ec3-8f97-6fdd8f1dc5f4

