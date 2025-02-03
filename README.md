# Layer Edge BOT
Layer Edge BOT

- Register Here : [Layer Edge](https://dashboard.layeredge.io/)
- Use Code : u9NH68wt

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Claim Daily Check-In
  - Auto Connect and Reconnect Node
  - Multi Accounts

## Requiremnets

- Make sure you have Python3.9 or higher installed and pip.

## Instalation

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/Not-D4rkCipherX/LayerEdge-v2.git
   ```
   ```bash
   cd LayerEdge-v2
   ```

2. **Install Requirements:**
   ```bash
   pip install -r requirements.txt 
   ```

## Configuration

- **accounts.txt:** You will find the file `accounts.txt` inside the project directory. Make sure `accounts.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    your_secret_key_1
    your_secret_key_2
  ```
- **proxy.txt:** You will find the `proxy.txt` file in the project directory. Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```
