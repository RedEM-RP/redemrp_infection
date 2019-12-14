# redemrp_infection
 A simple Armadillo Infection system for RedEM:RP

## 1. Description
This resource add's a disease in Armadillo

## 2. Installation
add ```ensure redemrp_infection``` to your server.cfg

## 3. Configuration
```
Config = {}
Config.msg = "You are getting sick..." -- Displays when Player is in infected area.
Config.TimeMax = 20000 -- How much time player can spend in Armadillo before getting hurt. DEFAULT: 5m
Config.HurtRefresh = 5000 -- Hurt Rate DEFAULT: 5sec
Config.HurtAmount = 3 -- How much amount should be player damaged by. DEFAULT: 3
Config.SafeTime = 90000 -- SafeTime after dead, player can't get hurt before time ends. DEFAULT: 1m 30s
Config.PlagueDistance = 65.0 -- Distance of the plague. DEFAULT: 65
```

## 4. Credits
[amakuu](https://github.com/amakuu/)
