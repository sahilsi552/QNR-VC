# QNR BOT
Fully working VC (user)Bot, based on py-tgcalls and py-tgcalls-wrapper with minimal [features](#TODO).   


## Deploying
* To heroku:   
[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://github.com/sahilsi552/QNR-VC)   

* Local machine/VPS:   
 `git clone https://github.com/sahilsi552/QNR-VC  
`pip install -r requirements.txt`   
`apt-get install ffmpeg`   
`touch .env && nano .env`, fill in the vars as in [.env.sample](./.env.sample)   
`python bot.py`   

## SESSION
Either run [sessiongen.py](./sessiongen.py) locally or run it on [repl.it by clicking here.](https://replit.com/@sahilsi552/QNR-PYROGRAM-REPL)
## Commands:   
- `!on` - Check if the (user)bot is online.   
- `!help` - Help message.   
- `!stream` - Either give a youtube URL or reply to a telegram file to play it.   
- `!pause` - Pause the stream.   
- `!resume` - Yes, resume.   




## TODO
(Contributions accepted, I'm lazy af.)    
- A queue system.   
- Play with song name.   
- Auto-leave VC on song end.   
- JoinVC/LeaveVC.   
- Updater.   


## Credits
- [Me](https://github.com/xditya)   
