# 🚀 One Click Multisynq Guide

Automate the setup and background running of the Multisynq Synchronizer CLI on Ubuntu 20.04/22.04 with a single script.

```
🔴 To get a synq key by you need:

Ping me ( @MuLtIsYnQ | Chuckles - Ping4Role  )
Include your Monad wallet address (0x...)
Link a tweet (or multiple tweets) that:
Mentions "multisynq" OR "fafnir" (can't be reused)
Includes your Discord username (only if not already verified)
Has 10+ followers on the Twitter account
Has 5+ likes on at least one tweet
All tweets must be from the same Twitter account
After getting your synq key: Use /verify to claim it!
```
---

## 🖥️ System Requirements

| Requirement     | Recommended Specs         |
|-----------------|--------------------------|
| **RAM**         | 4 GB                     |
| **CPU CORES**   | 2                        |
| **DISK**        | 10 GB NVMe (recommended) |


---

## 📦 Create an account

- https://startsynqing.com/profile/cuannode?ref=210b9d-8hw35m



---

## ⚡️ Installation

1. **Open a screen**

```bash
screen -S synq
  ```
2. **Run the command**

```bash
git clone https://github.com/arcxteam/multisynq-node && cd multisynq-node && chmod +x install.sh && sudo ./install.sh
  ```

3. **Follow all the prompts**

---

## 🖥️ Managing Your Synchronizer Session


- **View your running node:**
    ```bash
    screen -r synq
    ```
- **Detach and leave it running:**
    - Press `Ctrl+A`, then `D`

- **Check your node stats**
     ```bash
    synchronize web
     ```
  - Open the forwarded site to your node stats
    


---

## ℹ️ Notes

- If a `screen` session named `synq` already exists, the script will close it before starting a new one.
- The synchronizer runs even if you log out of your server or close your terminal.
- Current online nodes : https://map.startsynqing.com/
