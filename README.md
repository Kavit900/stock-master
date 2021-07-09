A Discord stock bot that provides daily news updates, chart informations and forecasting

## Technical Documentation
#### To use the bot locally
1. Install Python 3.6 or above. Install Python [here](https://www.python.org/).

2. If using git, run ```git clone https://github.com/Kavit900/stock-master```
3. Run ```pip3 install -r requirements.txt``` to install dependencies.
4. To configure the ```DISCORD_TOKEN```, configure it in ```CONFIG.py``` and edit the comments in ```bot.py```.
5. Run the bot with ```python3 bot.py```.

#### To invite the bot to a server
To add the bot to your server, go to this link and follow instructions. <https://discord.com/api/oauth2/authorize?client_id=861710886154797056&permissions=2148005952&scope=bot>

## User Documentation
**!** prefix

**graph** - Returns a tradingview link of a given stock symbol. Tradingview provides advanced charts and indicators for trading.

--- Example: !graph tsla

**chart** - Return a graph of a particular stock containing stock price for last 2 years.

--- Example: !chart msft

If no stock symbol is inputted for any commands, MSFT will be used by default.

**set_daily_news** -  Set the current channel to receive daily news update.

--- Example: !set_daily_news


In addition, the bot sends news headlines and the premarket movement of NASDAQ 100 everyday at 6:00 am PST.

#### To remove/hide a file that is already added to some previous commit and adding it to .gitignore is not helping
- git rm --cached -r <filename>

#### To enabled Bot deployed on Heroku
- Go to Resources tab.
- Click on the edit (pencil) button
- Switch on the dyno slider.
- Click on confirm.
