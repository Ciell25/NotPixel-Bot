> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/Van_Qish)

# Use Node.Js 18 or later

## 

| Functional                            | Supported |
| ------------------------------------- | :-------: |
| Auto paintiing                        |    ✅     |
| Claiming task                         |    ✅     |
| Multithreading                        |    ✅     |
| Caching session data                  |    ✅     |
| Using a session/query_id              |    ✅     |
| Binding a proxy to a session/query_id |    ✅     |
| Random sleep time between clicks      |    ✅     |


## [Settings](https://github.com/Ciell25/NotPixel-Bot/blob/main/.env-example)

| Settings                       | Description                                                                |
| ------------------------------ | -------------------------------------------------------------------------- |
| **API_ID / API_HASH**          | Platform data from which to launch a Telegram session (stock - Android)    |
| **AUTO_PAINT**                 | Whether the bot should paint (True / False)                                |
| **AUTO_CLAIM_TASKS**           | Whether the bot claim tasks (True / False)                                 |
| **AUTO_JOIN_SQUAD**            | Whether the bot should join sqaud (sessions only) (True / False)           |
| **SLEEP_BETWEEN_REQUESTS**     | Delay between taps in seconds (eg. [200, 700])                             |
| **DELAY_BETWEEN_STARTING_BOT** | Delay between starting in seconds (eg. [20, 30])                           |
| **DELAY_BETWEEN_PAINTING**     | Delay between painting in seconds (eg. [20, 30])                           |
| **DELAY_BETWEEN_TASKS**        | Delay between tasks in seconds (eg. [20, 30])                              |
| **USE_PROXY_FROM_JS_FILE**     | Whether to use proxy from the `bot/config/proxies.js` file (True / False)  |
| **USE_PROXY_FROM_TXT_FILE**    | Whether to use proxy from the `bot/config/proxies.txt` file (True / False) |

## Installation

You can download [**Repository**](https://github.com/Ciell25/NotPixel-Bot.git) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/Ciell25/NotPixel-Bot.git
~ >>> cd NotPixel-Bot

#Linux and MocOS
~/NotPixel-Bot >>> chmod +x check_node.sh
~/NotPixel-Bot >>> ./check_node.sh

OR

~/NotPixel-Bot >>> npm install
~/NotPixel-Bot >>> cp .env-example .env
~/NotPixel-Bot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/NotPixel-Bot >>> node index.js

#Windows
1. Double click on INSTALL.bat in NotPixel directory to install the dependencies
2. Double click on START.bat in NotPixel directory to start the bot

OR

~/NotPixel-Bot >>> npm install
~/NotPixel-Bot >>> cp .env-example .env
~/NotPixel-Bot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/NotPixel-Bot >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/NotPixel-Bot >>> node index.js --action=1

OR

~/NotPixel-Bot >>> node index.js --action=2 #session

OR

~/NotPixel-Bot >>> node index.js --action=3 #query_id

#1 - Create session
#2 - Run clicker
```
