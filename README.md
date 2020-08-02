# Discord.py File Server v1.0

The Discord.py File Server is a secure alternative to FTP or SMB file shares by running within the Discord API and transferring files as private direct messages instead of plaintext or ciphertext between 2 systems.  Files are sent to Users instead of IPs thus adding another layer of anonymity and users can view file contents from any of their devices. Access Control and Management is as simple as adding or removing users from the server as well.

**COMING SOON**: /create command to let you create a file and input text, /fileinfo to get filetype information from linux "file" command, file headers in /read

## Usage

To start the bot enter the directory and type ``` python3 bot.py ``` or ``` ./bot.py ``` if your have python3 in your /usr/bin

## Getting Started

Run ``` pip3 install -r requirements.txt ``` to install necessary libraries and create a new server in Discord, preferrably something such as "Discord File Server". Now go to the [Discord Applications Page](<https://discordapp.com/developers/applications/>) to create a new application and click "New Application" and name it something like "Discord File Server". Once created go to "Bot" in the left menu and click "Add Bot" and click "Copy" to get your Bot's private token. Now input this into the "TOKEN=" variable in bot.py. Lastly, add your bot to the server with "https://discordapp.com/api/oauth2/authorize?scope=bot&client_id=CLIENT_ID_NUMBER", run the bot.py file, and voila!

If you're getting random errors such as a **TypeError** enter ``` sudo python3 -m pip install -U discord.py ``` to update the Discord.py library (Discord recently pushed out a new update that changes the overwrites object).

## Built With

* Discord - Popular messaging platform for creating communities online
* Python 3.7 - Programming Language Developed by [Python](<https://python.org>)
* GitHub - This Website!

## Authors

* **Cisc0-gif** - *Main Contributor/Author*: Ecorp7@protonmail.com

## License

This project is licensed under the MIT License - see the LICENSE.txt file for details


## Acknowledgments

All credits are given to the authors and contributors to tools used in this software
