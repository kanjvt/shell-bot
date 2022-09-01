Shell Bot VPS Ubuntu

1. Install node.js

```
curl -sL https://deb.nodesource.com/setup_12.x | sudo -E bash -
sudo apt-get install nodejs
nodejs --version
```
2. install node-pty dependencies &  Clone repository
```
sudo apt install -y make python build-essential
git clone https://github.com/botgram/shell-bot.git && cd shell-bot
touch config.json && nano config.json
```
`paste with your bot`
```
{
    "authToken": "45365477:AAEw8ii-GsVqufGFHDFutgrvncA",
    "owner": 45643756
}
```
```
npm install
```
3. Install screen for keep alive
```
sudo apt install screen
screen -S runbottg
```

```
node server
```

`Bot Commands`
```
run - Execute command
enter - Send input lines to command
type - Type keys into command
control - Type Control+Letter
meta - Send the next typed key with Alt
keypad - Toggle keypad for special keys
redraw - Force the command to repaint
end - Send EOF to command
cancel - Interrupt command
kill - Send signal to process
status - View status and current settings
cd - Change directory
env - Manipulate the environment
shell - Change shell used to run commands
resize - Change the terminal size
setsilent - Enable / disable silent output
setlinkpreviews - Enable / disable link expansion
setinteractive - Enable / disable shell interactive flag
help - Get help
file - View and edit small text files
upload - Upload and overwrite raw files
r - Alias for /run or /enter
```
