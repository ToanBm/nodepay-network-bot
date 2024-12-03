# Nodepay Network Bot
## Prerequisites
- [Python](https://www.python.org/) (version 3.7 or higher)
## Installation
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/recitativonika/nodepay-network-bot.git
   ```
   ```bash
   cp -r nodepay-network-bot nodepay-network-bot-xx
   ```
2. Navigate to the project directory:
   ```bash
   cd nodepay-network-bot-xx
   ```
4. Install the necessary dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Register nodepay account first, if you dont have you can register [here](https://app.nodepay.ai/register?ref=RBjYajVO9U5p89W), I recomended to `download extension`, `activate your account`, complete the `Proof of Humanhood` and `connect your wallet` first before running the script because this important for `Nodepay TGE`.
2. Set and Modify `user.txt` before running the script. Below how to setup this file, put your np_token in the text file, example below:
	```
	eyJhbGcixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
	eyJ23wixxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
	```
	To get your token, follow this step:
	- Login to your grass account in https://app.nodepay.ai/dashboard, make sure you is in this link before go to next step
	- Go to inspect element, press F12 or right-click then pick inspect element in your browser
	- Go to application tab - look for Local Storage in storage list -> click `https://app.nodepay.ai` and you will see your np_token.
	- or you can go Console tab and paste this 
	```bash
	localStorage.getItem('np_token')
	```
3. If you want to use proxy, edit the `proxy.txt` with your proxy.
	```
	http://username:password@ip:port
	socks5://username:password@ip:port
 	```
4. Run the script:
   	```bash
	screen -S nodepay-xx
	```
	```bash
	python3 main.py
	```
6. When running the script, answer if you want to use proxy and how much proxy you want to use, it will look like this:
	```
 	Do you want to use proxies? (y/n): 

 	```
	```
	How many proxies per account do you want to use?: 
	```
## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Note
This script only for testing purpose, using this script might violates ToS and may get your account permanently banned.

My reff code if you want to use :) : 
https://app.nodepay.ai/register?ref=RBjYajVO9U5p89W
