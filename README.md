# Dawn Bot
Automated farming script for Dawn Validator using proxies, supporting multiple accounts.
### Tools and components required
1. Dawn Validator Account | Download [Dawn Validator Extension](https://chromewebstore.google.com/detail/dawn-validator-chrome-ext/fpdkjdnhkakefebpekbdhillbhonfjjp)
2. Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/signup.html``, insert Referral code ``mmwhsvp7`` and Register
3. VPS or RDP (OPTIONAL)
4. Python version 3.10 and above
## Getting Token
- Open ``chrome-extension://fpdkjdnhkakefebpekbdhillbhonfjjp/dashboard.html`` in your browser and login
- Press F12 or CTRL+SHIFT+I and Select Network
- Look for ``getpoint?appid=``
- Open request headers and copy the token. Bearer ``a1b2c3d4ef5g`` < your token
![image](https://github.com/user-attachments/assets/2cf7d088-8ecb-4925-a470-5b398cb88e1f)
- Insert your account details in ``accounts.txt``, with each line in the format ``email:token`` for each account, like:
```bash
email:token
email:token
email:token
```
# Installation
- Install Python For Windows: [Python](https://www.python.org/downloads/release/python-3110/)
- Install requirements, Windows:
```bash
pip install -r requirements.txt
```
```
### Run the Bot
- Replace the proxies example in ```proxies.txt``` to your own proxies
#### Run for single account
- Windows:
```bash
python main.py
```
- Select: 1
- Then insert your email and token
#### Run for multi accounts
- Windows:
```bash
python main.py
```
- Select: 2
# Notes
- Run this bot, and it will update your referrer code to my invite code if you don't have one.
- This bot have delay every 5 minutes. 
- You can just run this bot at your own risk, I'm not responsible for any loss or damage caused by this bot. This bot is for educational purposes only.

referral - mmwhsvp7
