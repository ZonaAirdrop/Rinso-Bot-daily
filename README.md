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
