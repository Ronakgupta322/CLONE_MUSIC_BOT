<p align="center">
  <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif"/>
</p>

<h2 align="center">
    ───「 ᴄʟᴏɴᴇ ᴍᴜsɪᴄ V3 」───
</h2>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<h1 align="center"><b><font color="red">𝐓ᴇᴀᴍ ʀᴏɴᴀᴋ 𝐁ᴏᴛs</font></b></h1>
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">


<p align="center"><a href="https://t.me/ronakgupta321"><img src="https://files.catbox.moe/b2mohj.jpg" width="400"></a></p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

</p>

<p align="center">
<b>𝗗𝗘𝗣𝗟𝗢𝗬𝗠𝗘𝗡𝗧 𝗠𝗘𝗧𝗛𝗢𝗗𝗦</b>
</p>

<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʜᴇʀᴏᴋᴜ 」─
</h3>

<p align="center"><a href="https://dashboard.heroku.com/new?template=https://github.com/Ronakgupta322/CLONE_MUSIC_BOT"> <img src="https://img.shields.io/badge/Deploy%20On%20Heroku-green?style=for-the-badge&logo=heroku" width="220" height="38.45"/></a></p>

<h1 align="center">🚩🚩 ᴊᴀɪ ѕʜʀᴇᴇ ʀᴀᴍ 🚩🚩</h1>

<h3 align="center">
    ─「 ᴅᴇᴩʟᴏʏ ᴏɴ ʟᴏᴄᴀʟ ʜᴏsᴛ / ᴠᴩs 」─
</h3>

- Get your [Necessary Variables](https://github.com/Ronakgupta322/CLONE_MUSIC_BOT/blob/main/sample.env)

### ⚠️ MongoDB URI — Apna Khud Ka Banao (Zaroori)

Har user ko apna **khud ka free MongoDB Atlas URI** use karna hoga. Shared/public URI use karne se `MongoDB not found` ya connection errors aate hain, isliye koi bhi ready-made URI is repo mein nahi diya gaya hai.

**Free MongoDB URI kaise banayein (5 minute mein):**

1. [MongoDB Atlas](https://www.mongodb.com/cloud/atlas/register) pe free account banao
2. **Create a new Cluster** → Free tier (M0) select karo → cluster create karo
3. Left menu se **Database Access** → **Add New Database User** → username/password set karo (password yaad rakho)
4. Left menu se **Network Access** → **Add IP Address** → **Allow Access From Anywhere** (`0.0.0.0/0`) select karo
   - Ye zaroori hai kyunki Heroku dynos ka IP fixed nahi hota — agar ye step skip kiya to hosting pe Mongo connect nahi hoga
5. **Database** → apne cluster pe **Connect** → **Drivers** → connection string copy karo, kuch aisa dikhega:
   ```
   mongodb+srv://<username>:<password>@cluster0.xxxxx.mongodb.net/?retryWrites=true&w=majority
   ```
6. `<username>` aur `<password>` ki jagah apna banaya hua username/password daalo
   - Agar password mein `@`, `#`, `%`, `/` jaise special characters hain to unhe [URL-encode](https://www.urlencoder.org/) karo, warna connection string kaam nahi karegi
7. Ye final string apne `.env` (ya Heroku Config Vars) mein `MONGO_DB_URI` ke aage paste kar do

Isse jo bhi is repo se apna bot host karega, usko koi Mongo conflict ya "not found" error nahi aayega, kyunki har user ka apna alag database rahega.

- Upgrade and Update by : `sudo apt-get update && sudo apt-get upgrade -y`

- Install Ffmpeg & Python by :
`sudo apt-get install python3-pip ffmpeg -y`

- Install pip by :
`sudo pip3 install -U pip`

- Install Node js by :
`curl -fssL https://deb.nodesource.com/setup_19.x | sudo -E bash - && sudo apt-get install nodejs -y && npm i -g npm`

- Clone the repository by :
`git clone https://github.com/Ronakgupta322/CLONE_MUSIC_BOT.git && cd CLONE_MUSIC_BOT`

- Install requirements by :
`pip3 install -U -r requirements.txt`

- Fill your variables in the env by :
`vi sample.env`<br>
Press `I` on the keyboard for editing env<br>
Press `Ctrl+C` when you're done with editing env and `:wq` to save the env<br>

- Rename the env file by :
`mv sample.env .env`

- Install tmux to keep running your bot when you close the terminal by :
`sudo apt install tmux && tmux`

- Finally run the bot by :
`bash start`
- For getting out from tmux session : Press `Ctrl+b` and then `d`<br>

━━━━━━━━━━━━━━━━━━━━

### Contact :
<a href="https://t.me/ronakgupta321"><img title="Telegram" src="https://img.shields.io/badge/Telegram-%23000000.svg?&style=for-the-badge&logo=telegram&logoColor=61DAFB"></a>

<a href="https://instagram.com/ronakgupta101"><img title="Instagram" src="https://img.shields.io/badge/instagram-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>
