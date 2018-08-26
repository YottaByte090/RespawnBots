# RespawnBots
> [rrrfffrrr님](https://github.com/rrrfffrrr/Insurgency-server-plugins)의 RespawnBots를 업그레이드한 모드입니다.  

* [Download Plugin](https://github.com/YottaByte090/RespawnBots/blob/master/RespawnBots.smx)  
* [Download Source](https://github.com/YottaByte090/RespawnBots/blob/master/RespawnBots.sp)  
* Copy [this file](https://github.com/YottaByte090/RespawnBots/blob/master/insurgency.games.txt) into (Source Mod Path)/gamedata/
 
## Cvars  
```
"sm_botrespawn_enabled"         "0"            // Enable respawn bots.
"sm_botrespawn_delay"	        "1"            // Delay to respawn, 0 will disable respawn.
"sm_botrespawn_rp"              "5"            // Default respawn point. Bot num is (Alive bot number) + sm_botrespawn_rp + (Player number) * sm_botrespawn_rp_add
"sm_botrespawn_rp_add"          "5"            // How many respawn point increase per players
"sm_botrespawn_display"         "1"            // Enable display how many bots remain. (Include respawn number)
"sm_botrespawn_display_delay"	"1"            // Display delay
"sm_botrespawn_message" "%i Insurgent(s) left" // The message that displays on the screen.
```

## Warning
* Max size of 'sm_botrespawn_message' is 128 Bytes.
* If you enabled 'sm_botrespawn_display', you **MUST** set 'sm_botrespawn_message'.
