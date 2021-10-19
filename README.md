# TelegramAutoMessageSender


## • Setup API
* Go to http://my.telegram.org  and log in.
* Click on API development tools and fill the required fields.
* put app name you want & select other in platform Example :
* copy "api_id" & "api_hash" after clicking create app ( will be used in setup.py )
<p><img src="https://i1.wp.com/python.gotrained.com/wp-content/uploads/2019/01/desc.png?resize=768%2C479&ssl=1"></p>

## • How To Install

`$ pkg install -y git python`

`$ git clone https://github.com/th3unkn0n/TeleGram-Scraper.git`

`$ cd TeleGram-Scraper`

`$ chmod +x * && python3 setup.py`

* To Genrate User Data

`$ python3 scrapr.py`

* ( members.csv is default if you changed name use it )
* Send Bulk sms To Collected Data 

`$ python3 smsbot.py members.csv`

* add users to your group

`$ python3 add2group.py members.csv`
