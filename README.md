# 🔗 MERK-BREP - Secure Messaging Relay System

[![Download MERK-BREP](https://img.shields.io/badge/Download-MERK--BREP-brightgreen)](https://github.com/Alpha284-coder/MERK-BREP)

MERK-BREP is a simple messaging system that helps you send messages safely. It uses servers that work together to keep your messages private. You do not need to connect directly to others. The system uses strong encryption to protect your communication.

---

## 📚 What is MERK-BREP?

MERK-BREP is a prototype of a new kind of messaging service. Instead of messages going directly from one person to another, they travel through a network of servers. These servers connect automatically and encrypt messages so only the receiver can read them. This makes your conversations secure and private.

This project focuses on using proven encryption methods and a system design that does not rely on a single point. Its goal is to let people communicate safely without needing to trust any single server.

---

## 🛠️ Features

- Uses AES-GCM encryption to keep messages private.
- End-to-end encrypted (E2EE) so no one else can read your chats.
- Works through multiple servers that form a "mesh network."
- Built with TypeScript for better reliability.
- Uses modern cryptography standards like Ed25519 and X25519.
- Communicates over websockets for stable message delivery.
- Designed to protect user privacy and avoid central control points.

---

## 💻 System Requirements

MERK-BREP runs on Windows computers. The following are the minimal requirements:

- Windows 10 or later (64-bit recommended)
- 4 GB RAM or more
- 200 MB of free disk space
- Internet connection for connecting to servers
- Modern web browser (Google Chrome, Firefox, Edge) if running the web client

---

## 🚀 Getting Started: Download and Setup

You will find the application on its GitHub page. Please follow these steps to download and run it on your Windows computer.

### 1. Visit the download page

Click this link to go to the MERK-BREP GitHub repository:

[![Download MERK-BREP](https://img.shields.io/badge/Download-MERK--BREP-blue)](https://github.com/Alpha284-coder/MERK-BREP)

This page has the latest version of the software.

### 2. Download the software

On the GitHub page, look for the section or folder named **Releases** or **Downloads**. If there is a file ending with `.exe` or `.zip`, download it to your PC by clicking on the link.

### 3. Run the installer or program

- If you downloaded an `.exe` file, double-click to start the setup. Follow the instructions on the screen.
- If it is a `.zip` file, right-click and choose "Extract All." Open the extracted folder and run the `.exe` or `.bat` file.

### 4. Allow permissions

During installation, the program may ask for permission to access your network or run on your computer. Allow these to let it work properly.

### 5. Open MERK-BREP

After installation, find MERK-BREP in the Start menu or on your desktop, and double-click to open.

### 6. Connect and start messaging

The app will connect to the server mesh automatically. You can now start sending messages safely.

---

## 🔧 How MERK-BREP Works

MERK-BREP connects clients to a group of servers that form a mesh. Each server talks to several others, and they share and pass encrypted messages. This creates a network that does not rely on any single server.

Your message gets encrypted on your device using AES-GCM encryption. Then, it goes through the mesh network encrypted. Only the person with the private key can decrypt and read the message.

The system uses modern cryptographic keys (Ed25519 for signatures, X25519 for key exchange) to make sure messages are safe and authentic.

---

## 🗂️ Files and Structure

After you download and install MERK-BREP, you will see some files and folders:

- **MERK-BREP.exe:** The main program you run.
- **config.json:** Settings for connecting to the server network. You can edit this if needed.
- **logs/:** Contains log files in case you need to check what the program is doing.
- **docs/:** Documentation files with technical details.

---

## ⚙️ Configuration Tips

Most users don’t need to change settings. The app connects automatically to the server mesh and handles encryption for you.

If you want to change connection options:

1. Open the `config.json` file using a simple text editor like Notepad.
2. You can adjust settings like:
   - Server list to connect to
   - Encryption options (usually no need to change)
   - Network ports if you have a firewall

Remember to save the file before running the app again.

---

## 🔄 Updating MERK-BREP

To update, revisit the GitHub download page. Download the latest `.exe` or `.zip` file and replace your old program with the new one.

It is a good idea to close the program before updating it.

---

## ❓ Troubleshooting

- The app cannot connect to servers: Check your internet connection or firewall settings.
- Messages don’t send or arrive: Restart the program or your computer.
- Errors appear during setup: Make sure you run the installer as an administrator.
- Program crashes on start: Verify your Windows is up to date and meets system requirements.

If problems continue, check the **logs/** folder for error messages and contact support through the GitHub page.

---

## 🔐 Security Notes

MERK-BREP uses strong encryption to protect your messages. Your private keys never leave your device. Messages travel encrypted through the network and are only unlocked by the intended recipient.

The system’s mesh network design reduces the chance of attacks or spying since no one server controls all data.

---

## 🧩 Supported Technologies and Topics

- **AES-GCM encryption:** Keeps messages secret.
- **Decentralized application:** No central server controls communication.
- **End-to-end encryption (E2EE):** Only sender and receiver can read messages.
- **Ed25519 / X25519 keys:** Modern cryptographic key pairs.
- **Websockets:** Keep messages flowing smoothly.
- **TypeScript:** Used for code that runs the app.
- **Relay servers:** Pass messages through the network.

---

## 🔗 Useful Links

- MERK-BREP Repository: https://github.com/Alpha284-coder/MERK-BREP  
- GitHub Releases Page (for downloads): https://github.com/Alpha284-coder/MERK-BREP/releases

---

## 🧑‍💻 Contact and Support

If you have questions, bugs, or want to contribute, use the GitHub repository. You can open issues or check existing discussions.  
The project is experimental and still growing, but feedback is welcome.