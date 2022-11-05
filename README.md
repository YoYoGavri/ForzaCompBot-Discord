
# ForzaCompBot - Discord

ForzaCompBot is an all in one Forza Discord Bot that is catered to the competitive Forza Horizon community. See below the current features that we currently offer!
To add the bot to your server, click [**here**](https://discord.com/api/oauth2/authorize?client_id=977343050651168788&permissions=126016&scope=bot%20applications.commands) to add FCB to your discord server. 

## Features

- Finding the WR Holder for a given FH4 - Fortune Island DLC Track
- Finding the WR Holder for a given FH4 - Lego Speed Champions DLC Track
- Finding the WR Holder for a given FH4 - Base Game Track
- Finding the WR Holder for a given FH5 - Base Game Track
- Finding the WR Holder for a given FH5 - Hot Wheels DLC Track
- FH5 Tested Tunes for B, A and S1 class
    - Tested on Horizon Mexico Circuit and Estadio
- More features to come, so hang tight!


## Documentation

A few cool features to know before running these commands:
- With the slash command migrate, all fields have type-hinting except `[track name]`
- `[track name]` can accept lowercase track names, and supports partial track name recognition. However, misspelling the track name will not yield a result

`/fh4 [class] [surface type] [track name]` - Get the current WR for a specified rivals track on FH4\
`/fh5 [class] [surface type] [track name]` - Get the current WR for a specified rivals track on FH5\
`/fortune [class] [surface type] [track name]` - Get the current WR for a specified rivals track on FH4 Fortune Island DLC\
`/hw [class] [surface type] [track name]` - Get the current WR for a specified rivals track on FH5 Hot Wheels DLC\
`/lego [class] [surface type] [track name]` - Get the current WR for a specified rivals track on FH4 Lego Speed Champions DLC\
`/tunes [class] [track] [sort] [name]` - Get the current WR for a specified rivals track on FH4
* `[track name]` only supports HMC and Estadio as arguments
* `[track name]` only supports Car and Tuner as arguments

`/help` - Retreive the current command list\
`/ping` - Command to test the latency of the bot, or to test if the bot is online\
`/bugreport` - Opens a bug form to fill out if a bug is present

`/spreadsheet` - Get the rivals and tunes spreadsheet where the bot pulls it's data\
`/submit` - Get the discord server link for the server which maintians the WR and Tunes records for submissions and the like



## FAQ

#### Why did I get a "The application did not respond" error?

There are several reasons why this error may occur. First, the bot may be offline. This should rarely occur, but things do happen and the bot may be offline for a short period of time. 
Second, there may be user error on the inputted command. Please make sure to type the fields correctly and click on any autofilling option if applicable.
Third, there is a bug with the system. If so, please fill out the form with `/bugreport` and it will be resolved in a timely manner.



## Authors

- This was all built by myself, so there may be bugs here and there. Check out my GitHub profile at [@yoyogavri](https://www.github.com/yoyogavri)


## Acknowledgements

 - Thank you to the Forza Horizon competitive community for allowing me to use their hard work to build this tool. Special thanks to Seasons, TopTierRamen, Kohl, Scaans, Logik, Egoism, Kcnaxii and Noobster for working with me to help get this tool off the ground.

