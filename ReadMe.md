##HashBuster Password Cracking Tool
HashBuster is a web-based password hash cracking tool that helps in identifying weak or commonly used passwords. Designed for ethical security assessments, it provides an intuitive interface for cracking hashes using dictionary attacks.

🔐 Features
Multi-Hash Algorithm Support: Supports popular hash types like MD5, SHA-1, SHA-256, and others.

Web-Based UI: Easy-to-use interface built with Node.js and Express.

Custom Wordlists: Upload your own wordlist to test password strength.

Real-Time Cracking Display: See progress and matched results dynamically.

📦 Installation
Clone the Repository

bash
Copy
Edit
git clone https://github.com/Nutika0975/HashBuster_Password_Cracking_tool.git
cd HashBuster_Password_Cracking_tool
Install Dependencies

bash
Copy
Edit
npm install
Start the Application

bash
Copy
Edit
npm start
Access the Tool

Open your browser and go to:
http://localhost:3000

🧠 Wordlist Requirement
The tool uses a dictionary-based attack, and it requires a wordlist file named:

Copy
Edit
rockyou.txt
⚠️ Note:
This file is not included in the repository due to its large size.

You can download rockyou.txt from trusted security resources such as:

SecLists

Kali Linux /usr/share/wordlists/rockyou.txt

Make sure to place the rockyou.txt file in the project directory.

🚀 Future Scope
GPU Acceleration: Speed up hash cracking using GPU via CUDA/OpenCL integration.

More Hashing Algorithms: Add support for bcrypt, NTLM, SHA-512, and custom hash formats.

Cloud Integration: Enable distributed cracking over multiple machines.

Session Management: Save and resume cracking sessions.

Logging and Reporting: Generate structured output reports of cracked hashes (planned).

🤝 Contributing
Contributions are welcome! Feel free to fork the repo and open a pull request with improvements or new features.

📜 License
This project is licensed under the MIT License. See the LICENSE file for details.

⚠️ Disclaimer
This tool is provided for educational and authorized penetration testing purposes only.
Do not use it on systems without explicit permission. Unauthorized use is illegal.
