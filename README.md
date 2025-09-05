🔐 Caesar Cipher Project

A simple web-based implementation of the Caesar Cipher encryption technique. This project provides:

Encryption & Decryption using a user-defined key

Brute-Force Decryption to crack encrypted text without a key

🚀 Features

Encrypt plain text using a Caesar shift key

Decrypt text with the correct shift key

Brute-force option to try all possible key values (0–25)

Simple and user-friendly interface built with HTML, CSS, and JavaScript

📂 Project Structure
├── index.html      # Main HTML file  
├── style.css       # Styling for the UI  
├── script.js       # Logic for encryption, decryption & brute force  
└── README.md       # Project documentation  

⚙️ How It Works

The Caesar Cipher shifts each letter of the plain text by a fixed number of positions in the alphabet.

Example (key = 3):

Plain: HELLO → Cipher: KHOOR

Decryption reverses the shift using the same key.

If the key is unknown, the brute-force option tries all possible shifts to reveal the correct message.

💻 Usage

Open index.html in any modern browser.

Enter your text in the input field.

Choose an option:

Encrypt → Provide a shift key and encrypt the message.

Decrypt → Provide the same shift key to get back the original message.

Brute Force → Run all possible shifts and view potential results.

🛠️ Tech Stack

HTML5

CSS3

JavaScript
