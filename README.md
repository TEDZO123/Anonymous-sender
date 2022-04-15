## Anonymous Sender Bot [@AnonySendBot](https://t.me/AnonySendBot)

<p align="center"><a href="https://github.com/STBOTZ/Anonymous-sender"><img src="https://telegra.ph/file/107ff8af751ad7b72e9b9.jpg" width="5000"></a></p>

Telegram bot to remove the forwarded tag from messages.

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

<details open="open">
  <summary> Table of Contents</summary>
  <ol>
    <li>
      <a href="#usage">Usage</a>
      <ul>
        <li><a href="#deploy-to-heroku">Deploy To Heroku</a></li>
        <li><a href="#local-deploying">Local Deploying</a></li>
      </ul>
    </li>
    <li>
      <a href="#environment-variables">Environment Variables</a>
      <ul>
        <li><a href="#mandatory-vars">Mandatory Vars</a></li>
        <li><a href="#optional-vars">Optional Vars</a></li>
      </ul>
    </li>
    <li><a href="#functions">Functions</a></li>
    <li><a href="#to-do">To-Do</a></li>
    <li><a href="#stats">Stats</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#credits">Credits</a></li>
    <li><a href="#support">Support</a></li>
  </ol>
</details>


## Usage

### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/STBOTZ/Anonymous-sender)

1. Tap on above button and fill `API_ID`, `API_HASH`, `BOT_TOKEN`.
2. Then tap "Deploy App" below it. Wait till deploying is complete (will take atmost 2 minutes).
3. After deploying is complete, tap on "Manage App"
4. Check the logs to see if your bot is ready!

### Local Deploying

1. Clone the repo
   ```markdown
   git clone https://github.com/STBOTZ/Anonymous-sender
   ```
2. Edit `Config.py` and fill the needed variables

3. Enter the directory
   ```markdown
   cd AnonymousSenderBot
   ```
4. Run the file
   ```markdown
   python3 anonbot.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)

## Functions

> More features soon, this is a minimal example :)

1) Removes the tag for everything including texts, images, stickers, videos, inline messages, documents and even polls, location, etc. 
2) Support to remove caption if you don't need the caption!! 
3) Specify owner's account to get help or something.

## To-Do

1) Add database to support Channel Posting easily
2) Add support to remove specific entities like Hashtags, URLs, etc. 
3) Support for bot stats in Telegram
4) Detect NSFW stuff to prevent take down of any bot.
5) Support for groups, message dump n banning

Support Channel :- @STBOTZ
Support Griup :- ST_BOTZ
