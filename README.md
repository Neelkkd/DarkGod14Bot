![DARKGOD14](https://i.imgur.com/aAXNvpf.jpg)

# DarkGod14Bot

<p align="center">
<a href="https://www.codacy.com/gh/DarkGod14/DarkGod14Bot/dashboard?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DarkGod14/DarkGod14Bot&amp;utm_campaign=Badge_Grade" alt="Codacy Badge">
<img src="https://app.codacy.com/project/badge/Grade/972e73015aaa4096bf109a79acae8afb" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="Libraries.io dependency status for GitHub repo"> <img src="https://img.shields.io/librariesio/github/DarkGod14/DarkGod14Bot?style=flat&logo=github&color=red" /> </a>
<a href="http://hits.dwyl.com/DarkGod14/DarkGod14Bot" alt="HitCount"> <img src="http://hits.dwyl.com/DarkGod14/DarkGod14Bot.svg" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot/network/members" alt="GitHub stars"> <img src="https://img.shields.io/github/stars/DarkGod14/DarkGod14Bot?style=flat&logo=github&color=yellow" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot/network/members" alt="GitHub forks"> <img src="https://img.shields.io/github/forks/DarkGod14/DarkGod14Bot" /> </a>
</p>
<p align="center">
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="GitHub commit activity"> <img src="https://img.shields.io/github/commit-activity/m/DarkGod14/DarkGod14Bot" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot/graphs/contributors" alt="GitHub contributors"> <img src="https://img.shields.io/github/contributors/DarkGod14/DarkGod14Bot?style=flat&logo=github" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="GitHub closed pull requests"> <img src="https://img.shields.io/github/issues-pr-closed-raw/DarkGod14/DarkGod14Bot?color=success" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="GitHub issues"> <img src="https://img.shields.io/github/issues-raw/DarkGod14/DarkGod14Bot?style=flat&logo=github&color=red" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="GitHub closed issues"> <img src="https://img.shields.io/github/issues-closed-raw/DarkGod14/DarkGod14Bot?style=flat&logo=github&color=success" /> </a>
</p>
<p align="center">
<a href="https://www.python.org/" alt="made-with-python"> <img src="https://img.shields.io/badge/made%20with-Python-1f425f.svg?style=flat&logo=python&color=blue" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="Python supported versions"> <img src="https://img.shields.io/badge/python-3.6%20%7C%203.7%20%7C%203.8%20%7C%203.9-blue" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="pypi version"> <img src="https://img.shields.io/badge/pypi-v13.5-blue" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot" alt="GitHub repo size"> <img src="https://img.shields.io/github/repo-size/DarkGod14/DarkGod14Bot" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot/blob/master/LICENSE" alt="GPLv3 license"> <img src="https://img.shields.io/github/license/DarkGod14/DarkGod14Bot?style=flat&logo=github&color=success" /> </a>
</p>
<p align="center">
<a href="" alt="DarkGod14"> <img src="https://img.shields.io/badge/built%20by-DarkGod14-blue" /> </a>
<a href="https://github.com/DarkGod14/DarkGod14Bot/graphs/commit-activity" alt="Maintenance"> <img src="https://img.shields.io/badge/maintained%3F-yes-blue.svg" /> </a>
<a href="https://makeapullrequest.com" alt="PRs Welcome"> <img src="https://img.shields.io/badge/PRs-welcome-blue.svg" /> </a>
</p>

A modular Telegram Python bot running on python3 with a sqlalchemy database.

Originally a AstrakoBott fork, DarkGod14Bot evolved further and was built to be more robust. 

* Bot link:  <a href="https://t.me/DarkGod14Bot" alt="DarkGod14Bot"> <img src="https://img.shields.io/badge/%F0%9F%A4%96%20-DarkGod14Bot-blue" /> </a>

* Support group:  <a href="https://t.me/DarkGod14BotSupport" alt="DarkGod14Bot Support"> <img src="https://aleen42.github.io/badges/src/telegram.svg" /> </a>

* Recommended federation:  <a href="https://t.me/DarkGod14BotSupport/558" alt="GodnessFed"> <img src="https://img.shields.io/badge/🚫-GodnessFed-red" /> </a>

In support group you can ask for help, discover/request new features, report bugs, and stay in the loop whenever a new update is available. 

## How to setup/deploy.

### Read these notes carefully before proceeding 
 - Edit any mentions of [@DarkGod14Bot Support](https://t.me/DarkGod14BotSupport) to your own support chat
 - Your code must be open source and a link to your fork's repository must be there in the start reply of the bot [See this](https://github.com/DarkGod14/DarkGod14Bot/blob/main/DarkGod14Bot/__main__.py#L13)
 - Lastly, if you are found to run this repo without the code being open sourced or the repository link not mentioned in the bot, we will push a gban for you in our network because of being in violation of the license, you are free to be a dick and not respect the open source code (we do not mind) but we will not be having you around our chats
 - This repo does not come with technical support, so DO NOT come to us asking help about deploy/console errors

 
 <details>
  <summary>Steps to deploy on Heroku !! </summary>

```
Fill in all the details, Deploy!
Now go to https://dashboard.heroku.com/apps/(app-name)/resources ( Replace (app-name) with your app name )
REMEMBER: Turn on worker dyno (Don't worry It's free :D) & Webhook
Now send the bot /start, If it doesn't respond go to https://dashboard.heroku.com/apps/(app-name)/settings and remove webhook and port.
```

  [![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/DarkGod14/DarkGod14Bot.git)

</details>  
 
<details>
  <summary>Steps to self Host!! </summary>

  ## Setting up the bot (Read this before trying to use!):
Please make sure to use python3.6, as I cannot guarantee everything will work as expected on older Python versions!
This is because markdown parsing is done by iterating through a dict, which is ordered by default in 3.6.

  ### Configuration

There are two possible ways of configuring your bot: a config.py file, or ENV variables.

The preferred version is to use a `config.py` file, as it makes it easier to see all your settings grouped together.
This file should be placed in your `DarkGod14Bot` folder, alongside the `__main__.py` file. 
This is where your bot token will be loaded from, as well as your database URI (if you're using a database), and most of
your other settings.

It is recommended to import sample_config and extend the Config class, as this will ensure your config contains all
defaults set in the sample_config, hence making it easier to upgrade.

An example `config.py` file could be:
```
from DarkGod14Bot.sample_config import Config

class Development(Config):
    OWNER_ID = 254318997  # your telegram ID
    OWNER_USERNAME = "SonOfLars"  # your telegram username
    API_KEY = "your bot api key"  # your api key, as provided by the @botfather
    SQLALCHEMY_DATABASE_URI = 'postgresql://username:password@localhost:5432/database'  # sample db credentials
    JOIN_LOGGER = '-1234567890' # some group chat that your bot is a member of
    USE_JOIN_LOGGER = True
    SUDO_USERS = [18673980, 83489514]  # List of id's for users which have sudo access to the bot.
    LOAD = []
    NO_LOAD = ['translation']
```

If you can't have a config.py file (EG on Heroku), it is also possible to use environment variables.
So just go and read the config sample file. 

  ### Python dependencies

Install the necessary Python dependencies by moving to the project directory and running:

`pip3 install -r requirements.txt`

This will install all the necessary python packages.

  ### Database

If you wish to use a database-dependent module (eg: locks, notes, userinfo, users, filters, welcomes),
you'll need to have a database installed on your system. I use Postgres, so I recommend using it for optimal compatibility.

In the case of Postgres, this is how you would set up a database on a Debian/ubuntu system. Other distributions may vary.

- install postgresql:

`sudo apt-get update && sudo apt-get install postgresql`

- change to the Postgres user:

`sudo su - postgres`

- create a new database user (change YOUR_USER appropriately):

`createuser -P -s -e YOUR_USER`

This will be followed by you need to input your password.

- create a new database table:

`createdb -O YOUR_USER YOUR_DB_NAME`

Change YOUR_USER and YOUR_DB_NAME appropriately.

- finally:

`psql YOUR_DB_NAME -h YOUR_HOST YOUR_USER`

This will allow you to connect to your database via your terminal.
By default, YOUR_HOST should be 0.0.0.0:5432.

You should now be able to build your database URI. This will be:

`sqldbtype://username:pw@hostname:port/db_name`

Replace sqldbtype with whichever DB you're using (eg Postgres, MySQL, SQLite, etc)
repeat for your username, password, hostname (localhost?), port (5432?), and DB name.

  ## Modules
   ### Setting load order.

The module load order can be changed via the `LOAD` and `NO_LOAD` configuration settings.
These should both represent lists.

If `LOAD` is an empty list, all modules in `modules/` will be selected for loading by default.

If `NO_LOAD` is not present or is an empty list, all modules selected for loading will be loaded.

If a module is in both `LOAD` and `NO_LOAD`, the module will not be loaded - `NO_LOAD` takes priority.

   ### Creating your own modules.

Creating a module has been simplified as much as possible - but do not hesitate to suggest further simplification.

All that is needed is that your .py file is in the modules folder.

To add commands, make sure to import the dispatcher via

`from DarkGod14Bot import dispatcher`.

You can then add commands using the usual

`dispatcher.add_handler()`.

Assigning the `__help__` variable to a string describing this modules' available
commands will allow the bot to load it and add the documentation for
your module to the `/help` command. Setting the `__mod_name__` variable will also allow you to use a nicer, user-friendly name for a module.

The `__migrate__()` function is used for migrating chats - when a chat is upgraded to a supergroup, the ID changes, so 
it is necessary to migrate it in the DB.

The `__stats__()` function is for retrieving module statistics, eg number of users, number of chats. This is accessed 
through the `/stats` command, which is only available to the bot owner.

## Starting the bot.

Once you've set up your database and your configuration is complete, simply run the bat file(if on windows) or run (Linux):

`python3 -m DarkGod14Bot`

You can use [nssm](https://nssm.cc/usage) to install the bot as service on windows and set it to restart on /gitpull 
Make sure to edit the start and restart bats to your needs. 
Note: the restart bat requires that User account control be disabled.

For queries or any issues regarding the bot please open an issue ticket or visit us at [DarkGod14Bot Support](https://t.me/DarkGod14BotSupport)
## How to setup on Heroku 
For starters click on this button 

## Credits
The bot is based on the original work done by [PaulSonOfLars](https://github.com/PaulSonOfLars)
This repo was just revamped to suit an Anime-centric community. All original credits go to Paul and his dedication, Without his efforts, this fork would not have been possible!

Also, missing proper credit for blacklistusers taken from TheRealPhoenixBot (will add it later, this note says unless it is done)

Any other authorship/credits can be seen through the commits.

Should any be missing kindly let us know at [DarkGod14Bot Support](https://t.me/DarkGod14BotSupport) or simply submit a pull request on the readme.
