# BOT RINSO AUTO DAILY 

📝 Feature 
- Support VPS & Termux 
- Proky Support
- Multi account Support
- Bot Auto Daily to get exp

- For VPS Create `screen`

````
screen -S rinso
````
- Let the bot run, then detach from the screen

`Ctrl + A then press DCtrl + A then press D`

- To return to the screen

````
screen -r rinso
````

*🖥️ Start installation*

````
git clone https://github.com/ZonaAirdrop/Rinso-Bot-daily.git
cd Rinso-Bot-daily
npm install
````
*🔖(Optional) Add Proxies*

````
nano proxies.txt
````
- Supported formats

````
http://user:pass@ip:port 
````

*🔖 Create Folder* `accounts.txt`

````
nano accounts.txt
````
`Privatekey.zealy id`

*🔖Running Bot*

````
node index.js
````
✅
- For Termux If an Error Occurs in ethers

`Install ethers`

````
npm install ethers --save
````
- if an error occurs in ora install
`Install ora`

````
npm install ora --save
````

🗿 Tutorial Get ID Zealy 

*open Zealy and be on profil*
[![IMG-20250602-113153-131.jpg](https://i.postimg.cc/g0MDrPsq/IMG-20250602-113153-131.jpg)](https://postimg.cc/f39Xgp6J)

*Open devtools* see the picture below 
- Click Profil
[![IMG-20250602-113238.jpg](https://i.postimg.cc/L4gT4w1L/IMG-20250602-113238.jpg)](https://postimg.cc/rzcWQhgw)

*You will see this copy from* start: eyj ; 
[![IMG-20250602-113326.jpg](https://i.postimg.cc/mkmNxbyG/IMG-20250602-113326.jpg)](https://postimg.cc/FkJJ3X6P)

After copying, open this link: https://jwt.io/ Paste the code you copied earlier

*You will find an id like this*
[![IMG-20250602-113419.jpg](https://i.postimg.cc/xTWNXJC4/IMG-20250602-113419.jpg)](https://postimg.cc/rKNwbp51)

private key example in bot: privatkeyxxxxxxxx,222-171- id Zealy 

⚠️Notes

ONLY use testnet wallets
NEVER paste mainnet private keys
This bot runs indefinitely (use Ctrl + C to stop)
Testnet = Zero gas cost
Randomized delays between operations for safety
👉 Join Chanel https://t.me/ZonaAirdr0p
