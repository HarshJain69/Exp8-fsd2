# JWT Auth Full Stack Application

## Overview
React frontend connects to backend APIs
JWT stored in sessionStorage
Protected routes accessed using token
Logout clears session

## Project Structure
```text
/
├── backend/
│   ├── server.js
│   └── package.json
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Login.js
│   │   │   └── Dashboard.js
│   │   ├── App.js
│   │   ├── index.js
│   │   └── index.css
│   └── package.json
├── run_mac_linux.sh
└── run_windows.bat
```

## How to Run

### On macOS / Linux
Open your terminal in the root of the project and run:
```bash
chmod +x run_mac_linux.sh
./run_mac_linux.sh
```

### On Windows
Double click the `run_windows.bat` file or run it in your command prompt:
```cmd
run_windows.bat
```

## Credentials

The backend comes with hardcoded demo credentials:
* **Admin:** `admin` / `admin123`
* **User:** `user` / `user123`
