# TeleDDoS
This bot runs in golang and creates a bot and a webserver for sending ddos attack from with an api handler, autopay, and its fast! 

in order to start the bot you must disable any webserver currently running, this is because the src makes its own webserver for the api handler!
next your going to want to install golang 1.21.4 and install all the other dependancys

1. get token from @BotFather
2. change the settings and apply it for payments
3. input the bot_token and shop_token in the config.json file
4. run the program `go run .`

dont compiled the code itll messup alot of it

`screen go run . (sudo)`

just click start and itll automatically add your account!
to update your user go into 

`master > config.json`

and edit the "live": true to "live": false and this will disable any admin restrictions, update your user with /update 'username' role 1 (for admin)
make sure you turn live mode back off, this bot opens a ssh server you can disable in the config file, it has no purpose at the moment.


i relized this bot needs a remake because of the way it runs every function and opens the db not just opening the db for specific functions, i hope this teaches yall sum like it thought me 




credits to @lolinekos & @pxzdano for helping me

@FileGone on telegram for more code || selling twilight.lol 500$
