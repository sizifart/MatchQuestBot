# MatchQuestBot
🖱️ clicker for [https://t.me/MatchQuestBot](https://t.me/MatchQuestBot/start?startapp=177ef097049224f890951776a8466de4)


## Functionality
| Functional                                                                      | Supported |
|----------------------------------------------------------------|:---------:|
| Auto Claim                                                     |     ✅     |
| Use Daily Booster                                              |     ✅     |
| Multi Account Support                                          |     ✅     |
| Auto Playing Game Support                                      |     ✅     |


## About Config.json

Here some key parameter to enable some feature

| parameter         | value        | description                           |
| ----------------- | ------------ | ------------------------------------- |
| use_daily_booster | (true/false) | use daily booster                     |
| auto_play_game    | (true/false) | use this for enable auto playing game |


## Settings data file
| Setting                      | Description                                                                                    |
|------------------------------|------------------------------------------------------------------------------------------------|
| query_id        | fill the `data.txt` file with your data, how to get data you can refer to [How to Get Data](#how-to-get-data)                      |


## Requirements
- Python 3.9 (you can install it [here](https://www.python.org/downloads/release/python-390/)) 
- How to Get Data (you can get them [here](#how-to-get-data))
  
## Auto Install/Run
- Click on Install.bat to automatically install the required dependencies 
- Then click on START.bat to run the project

## Menual Install/Run
1. Run the bot:
   ```bash
   python bot.py
   ```

# How to Get Data
   
   1. Active web inspecting in telegram app
   2. Goto bot and open the apps
   3. Press `F12` on your keyboard to open devtool or right click on app and select `Inspect`
   4. Goto `console` menu and copy [javascript code](#javascript-command-to-get-telegram-data-for-desktop) then paste on `console` menu
   5. If you don't receive error message, it means you successfully copy telegram data then paste on `data.txt` (1 line for 1 telegram data)
   
   Example telegram data

   ```
   query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

   6. If you want to add more account. Just paste telegram second account data in line number 2.
   
   Maybe like this sample in below

   ```
   1.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   2.query_id=xxxxxxxxxx&user=xxxxxxfirst_namexxxxxlast_namexxxxxxxusernamexxxxxxxlanguage_codexxxxxxxallows_write_to_pmxxxxxxx&auth_date=xxxxxx&hash=xxxxxxxxxxxxxxxxxxxxx
   ```

# Javascript Command to Get Telegram Data for Desktop

```javascript
copy(Telegram.WebApp.initData)
```
 
# Telegram Channel

✅ Channel for information and training on Telegram airdrop bots 🔷 Follow us on Telegram : [SIZIFAIRDROP](https://t.me/sizifairdrop)

# Discussion

If you have an question or something you can ask in here : [F.Davoodi](https://t.me/sizifart)

