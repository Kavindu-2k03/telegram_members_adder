
Using this tool you can easily add so many members from any group to your group. Less than 2 minutes. Super easy. Time saver. But this tool is only for educational purpose. You could be banned from Telegram. So be careful. Recommanded to use this tool only on Termux.


## How to Setup API:
- Go to https://my.telegram.org and Login.
- Click on API development tools and fill the required fields.
- Put app name you want & select Other in Platform.
- After clicking Create App, Copy "api_id" & "api_hash" from there. (This will be used in `setup.py`)
<p><img src="https://i1.wp.com/python.gotrained.com/wp-content/uploads/2019/01/desc.png?resize=768%2C479&ssl=1"></p>

## How To Install? (Only for Termux!):

$ `pkg install git python -y`

$ `git clone https://github.com/Kavindu-2k03/telegram_members_adder.git`

$ `cd telegram_members_adder`

$ `chmod +x * && python3 setup.py`

## To Genrate User Data:

$ `python3 scraper.py`

- (`members.csv` is default if you changed name use it)
- Send Bulk SMS To Collected Data

$ `python3 smsbot.py members.csv` [Optional]

- Add users to your group

$ `python3 adder.py `

#### Or,

$ `python3 addtogroup.py members.csv`

---
