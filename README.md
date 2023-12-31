# [CS2] Game-Manager (1.0.4)

### Game Manager ( Block/Hide , Messages , Ping , Radio , Connect , Disconnect , Sounds , Restart On Last Player Disconnect , Map Rotation , And More )

![3](https://github.com/oqyh/cs2-Game-Manager/assets/48490385/76d08c47-d838-4867-8410-06b7c8249add)
![2](https://github.com/oqyh/cs2-Game-Manager/assets/48490385/1d2c9311-3092-4c49-8198-b37d3cb65890)
![1](https://github.com/oqyh/cs2-Game-Manager/assets/48490385/65c8b2d0-045a-46d2-b75a-a2c235fc6a26)
![4](https://github.com/oqyh/cs2-Game-Manager/assets/48490385/138b8ff5-df2e-4c3a-a85a-f8996aeda63b)
![111](https://github.com/oqyh/cs2-Game-Manager/assets/48490385/52c68d54-9981-4c7e-898d-1f423caa621e)


## .:[ Dependencies ]:.
[Metamod:Source (2.x)](https://www.sourcemm.net/downloads.php/?branch=master)

[CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp/releases)

## .:[ Configuration ]:.
```json
{
  "DisableRadio": false,
  "DisableGrenadeRadio": false,
  "DisablePing": false,
  "DisableChatWheel": false,
  "DisableKillfeed": false,
  "DisableRadar": false,
  "DisableMoneyHUD": false,
  "DisableTeamMateHeadTag": 0, // (1) = Remove Head Tag Only Behind Wall || (2) = Remove Head Tag Completely
  "DisableWinOrLosePanel": false,
  "DisableWinOrLoseSound": false,
  "DisableJumpLandSound": false,
  "DisableFallDamage": false,
  "DisableLegs": false,
  "DisableSvCheats": false, // Force sv_cheats 0
  "DisableRewardMoneyMessages": false,
  
//-----------------------------------------------------------------------------------------

  "IgnoreDefaultDisconnectMessages": false,
  "IgnoreDefaultJoinTeamMessages": false,
  
//-----------------------------------------------------------------------------------------

  //{PLAYERNAME} == Player Name Who Joinned The Team
  //Colors Available = {default} {white} {darkred} {green} {lightyellow} {lightblue} {olive} {lime} {red} {lightpurple}
                      //{purple} {grey} {yellow} {gold} {silver} {blue} {darkblue} {bluegrey} {magenta} {lightred} {orange}
					  
  "CustomJoinTeamMessages": false,
  "CustomJoinTeamMessagesCT": "{green}Gold KingZ {grey}| {purple}{PLAYERNAME} {grey}is joining the {lime}Counter-Terrorists",
  "CustomJoinTeamMessagesT": "{green}Gold KingZ {grey}| {purple}{PLAYERNAME} {grey}is joining the {lime}Terrorists",
  "CustomJoinTeamMessagesSpec": "{green}Gold KingZ {grey}| {purple}{PLAYERNAME} {grey}is joining the {lime}Spectators",
  
//-----------------------------------------------------------------------------------------

  // ((MUST Disable This sv_hibernate_when_empty OTHERWISE WILL NOT WORK ))
  //Restart The Server If (RestartWhenXPlayersInServerORLess) After (RestartXTimerInMins)
  //RestartServerMode (1) = Restart Method
  //RestartServerMode (2) = Crash Method Sometimes Restart Will Not Work Use This Method Instead
  "RestartServerMode": 0,
  "RestartXTimerInMins": 5,
  "RestartWhenXPlayersInServerORLess": 0,
  
//-----------------------------------------------------------------------------------------

  // ((MUST Disable This sv_hibernate_when_empty OTHERWISE WILL NOT WORK ))
  //Rotate Maps Server If (RotationWhenXPlayersInServerORLess) After (RotationXTimerInMins)
  //RotationServerMode (1) = Get Maps From Top To Bottom In RotationServerMapList.txt
  //RotationServerMode (2) = Get Random Maps In RotationServerMapList.txt
  "RotationServerMode": 0,
  "RotationXTimerInMins": 8,
  "RotationWhenXPlayersInServerORLess": 0,
  
//-----------------------------------------------------------------------------------------
  "ConfigVersion": 1
}
```


## .:[ Change Log ]:.
```
(1.0.4)
-Added "DisableTeamMateHeadTag"
-Added "DisableSvCheats"
-Added "CustomJoinTeamMessages"
-Added "CustomJoinTeamMessagesCT"
-Added "CustomJoinTeamMessagesT"
-Added "CustomJoinTeamMessagesSpec"
-Added "RotationServerMode"
-Added "RotationXTimerInMins"
-Added "RotationWhenXPlayersInServerORLess"

-Fix / Remove Some Bugs

(1.0.3)
-Added [RestartServerLastPlayerDisconnect]
-Added [RestartMethod]
-Added [RestartXTimerInMins]
-Added [RestartWhenXPlayersInServerORLess]

(1.0.2)
-Added [DisableLegs]
-Fix [IgnoreRewardMoneyMessages]
-Fix [IgnoreTeamMateAttackMessages]
-Fix [IgnorePlayerSavedYouByPlayerMessages]

(1.0.1)
-Added [DisableGrenadeRadio]
-Added [DisableRadar]
-Added [DisableMoneyHUD]
-Added [DisableJumpLandSound]
-Added [DisableFallDamage]
-Added [IgnoreRewardMoneyMessages]
-Added [IgnoreTeamMateAttackMessages]
-Added [IgnorePlayerSavedYouByPlayerMessages]

(1.0.0)
-Initial Release
```

## .:[ Donation ]:.

If this project help you reduce time to develop, you can give me a cup of coffee :)

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://paypal.me/oQYh)
