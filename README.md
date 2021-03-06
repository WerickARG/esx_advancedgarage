# About esx_advancedgarage:
Advanced Garage System for ESX

This Code has been completely re-worked. ESX Advanced Garage supports Cars, Boats, & Aircrafts. This Garage Script only takes into account the Vehicles Purchased through `esx_vehicleshop` & `esx_advancedvehicleshop`. Players can also go to the Impound to retrieve their Vehicles if its lost or Destroyed for a Fee.

# Look in the Wiki before submitting Issues. (Failure to abide by this will result in Block)
* [Added Wiki that has the Common Problems Fixed](https://github.com/HumanTree92/esx_advancedgarage/wiki)
* Also if you are using Zap-Hosting I will not help with your issues at all. Zap is trash. If you want a great Server go somewhere else.

# Helpfull Info:
* Unable to Store Vehicles you don't own.
* Ability to Kick people who try to Cheat using the Garage & Set Custom Kick Message.
* Private Property Garages.
* Ambulance, Police, Aircraft, Boat, & Car Garages.
* Ambulance, Police, Aircraft, Boat, & Car Impounds.

# Requirements:
* Required:
  * [es_extended](https://github.com/ESX-Org/es_extended)
  * [esx_property](https://github.com/ESX-Org/esx_property)
* Optional:
  * [esx_advancedvehicleshop](https://github.com/HumanTree92/esx_advancedvehicleshop)
  * [esx_vehicleshop](https://github.com/ESX-Org/esx_vehicleshop)
  * [esx_mechanicjob](https://github.com/ESX-Org/esx_mechanicjob)

# Download & Installation:
1) Download the .zip.
2) Extract the .zip or Open the .zip.
3) Import the `esx_vehicleshop_fix.sql` into your database if using with esx_vehicleshop or edit your Database & change your job to NOT NULL & DEFAULT civ
3) Place `esx_advancedgarage` in your ESX Directory
4) Add `start esx_advancedgarage` to your server.cfg

# KNOWN BUGS:
* There is a Limit on how many Vehicles that can be in each garage. For me it was 36 Vehicles in the Car Garage but after that i couldn't pull anymore out. You can still buy more Boats & Planes if the Car Garage is at 36.
* It is Possible to Duplicate Vehicles but do note that if said Person Duplicates a Vehicle & takes 1 of them & sell thems the other one is useless & can NOT be stored or sold.
* Doesn't work well when using the Car Dealer Job.
* If you are having problems with the SQL from esx_vehicleshop try the SQL from here. If a problem with the SQL from here try esx_vehicleshop SQL. If still having problems please submit an issue.

# Other Scripts:
If you like this please check out some of my other stuff like
* [esx_advancedgarage](https://github.com/HumanTree92/esx_advancedgarage)
* [esx_advancedvehicleshop](https://github.com/HumanTree92/esx_advancedvehicleshop)
* [esx_advancedhospital](https://github.com/HumanTree92/esx_advancedhospital)
* [esx_advancedweaponshop](https://github.com/HumanTree92/esx_advancedweaponshop)
* [esx_advancedfuel](https://github.com/HumanTree92/esx_advancedfuel)
* [esx_extraitems](https://github.com/HumanTree92/esx_extraitems)
* [esx_licenseshop](https://github.com/HumanTree92/esx_licenseshop)
* [esx_vehiclespawner](https://github.com/HumanTree92/esx_vehiclespawner)
* [FiveM_CustomMapAddons](https://github.com/HumanTree92/FiveM_CustomMapAddons)

# Archived Scripts:
Scripts that will no longer be Maintained.
* [esx_aircraftshop](https://github.com/HumanTree92/esx_aircraftshop)
* [esx_boatshop](https://github.com/HumanTree92/esx_boatshop)
* [esx_truckshop](https://github.com/HumanTree92/esx_truckshop)
* [esx_plasticsurgery](https://github.com/HumanTree92/esx_plasticsurgery)
* [esx_hospital](https://github.com/HumanTree92/esx_hospital)
* [esx_panicbutton](https://github.com/HumanTree92/esx_panicbutton)

# Visit Velociti Entertainment:
* TS3 - ts3.velocitientertainment.com
* [Discord](http://discord.velocitientertainment.com)
* [Website](http://velocitientertainment.com/)
* [Forums](http://velocitientertainment.com/forum)
* [About Us](http://velocitientertainment.com/pc-gaming/)
* [Donate](http://velocitientertainment.com/donations/)
* [Steam Group](http://steamcommunity.com/groups/velocitientertainment)
* [Facebook](http://facebook.com/VelocitiEntertainment)
* [Twitter](http://twitter.com/VelocitiEnt)
* [YouTube](http://youtube.com/user/HumanTree92)
* [Twitch](http://twitch.tv/humantree92)
* [eBay](http://ebay.com/usr/humantree92)

# Legal
### License
esx_advancedgarage - Advanced Garage for ESX

Copyright (C) 2011-2020 Velociti Entertainment

This program Is free software: you can redistribute it And/Or modify it under the terms Of the GNU General Public License As published by the Free Software Foundation, either version 3 Of the License, Or (at your option) any later version.

This program Is distributed In the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty Of MERCHANTABILITY Or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License For more details.

You should have received a copy Of the GNU General Public License along with this program. If Not, see http://www.gnu.org/licenses/.
