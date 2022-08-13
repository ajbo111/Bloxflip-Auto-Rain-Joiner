# Bloxflip-auto-rain-joiner

## ARJ v1.0:
- Bug Fixed


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Information:
- When there is a rain at [bloxflip](https://bloxflip.com) this program will join the rain and let you know some information about it
- If you want to use it check license so you know your limits
- If you dont trust it, its literally open source

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Installation:
1) download the latest version of the program
2) Extract the files to a foler of your choice
3) run the **"installer.bat"** file and it should start running


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Notes:
- Best If Ran Overnight or on a another unused pc on the side.


-----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Config guide:

Default config.json file:
```json
{
  "minimum_amount": 500,
  "refresh_rate": 30,
  "mouse_movement": "True",
  "windows_notification": "True",
  "webhook_enabled": "False",
  "webhook_ping": "<@6666666>",
  "webhook": "https://discord.com/xxxxxxxxxxxxxx",
  "authorization": "authtoken"
}
```
### minimum_amount:
Minimum rain amount intended for the program



### refresh_rate:
How often you want it to check if there is a rain


### mouse_movement:
If set to "True" it will move your mouse This helps get past botfail



### webhook_enabled:
Should be obvious but if you want the rain notifier to send a message to your discord webhook set it to "True"


### webhook:
If you set webhook_enabled to "True" input your webhook into here to it can actually send it to you

Example of webhook:


### authorization:
This is your bloxflip login token, this is used to get your username and robloxid.

- To get this head to [bloxflip](https://bloxflip.com).
- Next press the "F12" key on your keyboard or "CTRL + SHIFT + I"
- Now make sure "console" is selected, if not just click on it (image attached)



- Next paste in the code below
```
copy(localStorage.getItem('_DO_NOT_SHARE_BLOXFLIP_TOKEN'))
```
- You should now have your bloxflip token copied to your clipboard, just open your config file and paste it inbetween the quotation marks.

## Current Issues:
- Some rains fail to join.
