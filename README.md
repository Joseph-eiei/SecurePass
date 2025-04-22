# SecurePass 💻 

A simple, offline-capable password manager. Users sign up, log in, and store encrypted credentials locally in a SQLite database, with AES encryption handled in the browser.

It is developed as a project for Computer and Network Security (DES332) Sec. 1 at Sirindhorn International Institute of Technology (SIIT), Thammasat University.

## Tech Stack
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Node.js, Express, SQLite3
- **Auth & Security:** bcrypt (password hashing), CryptoJS (AES encryption in frontend)

## How to Run
1. **Clone repository**
    ```
    git clone https://github.com/Joseph-eiei/SecurePass.git
    ```
2. **Install dependencies**
   ```
   npm i
   ```
3. **Start the server**
   ```
   node server.js
   ```
4. **Use the app**
   Open your browser to `http://localhost:3000/` to create an account, then log in at `login.html` and manage your vault in `main.html`.
