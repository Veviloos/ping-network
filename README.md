# Ping Network Auto Bot

![image](https://github.com/user-attachments/assets/5c8ec54b-9181-4046-8bae-88e2ca69ac86)

## Register Link : [HERE](https://t.me/hiddengemnews/13783)

## Features ✨

- Automated WebSocket connection to Ping Network
- Random zone selection for each session
- Dynamic User-Agent generation
- Analytics event tracking
- Automatic reconnection with exponential backoff
- Real-time points tracking
- Referral points monitoring

## Prerequisites 📋

- Node.js v16+
- npm/yarn
- Git

## Installation 🛠️

1. Clone the repository:
```
git clone https://github.com/BidyutRoy2/ping-network.git
cd ping-network
```

2. Install dependencies:
```
npm install
```

3. Open .env File and Save Your Ping Netwrok User ID (CTRL+X+Y+ENTER)

```
nano .env
```

```
USER_ID= Your Ping Network user ID 12345
DEVICE_ID= Will be auto-generated if empty
```

4. How to Find Your User ID
- Open Extsnsion in Browser
```
chrome-extension://geeedmdpncfeomhgbjeafcahepjelimg/popup.html
```
- Open Inspact Mode (Ctrl + Shift + C)
  
![image](https://github.com/user-attachments/assets/29e56f2f-ce84-45a0-aed5-583e5d4e09f7)


5. Start the bot
```bash
npm start
```

The bot will:
- Generate a unique device ID if none exists
- Connect to Ping Network's WebSocket
- Send periodic analytics events
- Maintain connection with heartbeat pings
- Automatically reconnect if disconnected

## Logging 📝

The bot provides color-coded console output:
- ✅ Success messages
- ⚠ Warning messages
- ✗ Error messages
- ⟳ Loading/process messages
- ➤ Step-by-step execution
