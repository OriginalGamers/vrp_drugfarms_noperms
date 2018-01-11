# vrp_drugfarms
This is not my script! The original script can be found here -=- https://github.com/D3uxx/vrp_drugfarms -=- (permissions given)

I have just removed the permissions and translated the script to english. I have not translated the permissions portion since I am not using it. Uncomment the parts noted in the code and add the below.

Thank you!

Add the following groups to /vrp/cfg/groups.lua
```
  ["marihuana"] = {
  _config = {onspawn = function(player) vRPclient.notify(player,{"Eres marihuanero."}) end},
  }, 

  ["blanqueo"] = {
  _config = {onspawn = function(player) vRPclient.notify(player,{"Tu eres un blanqueadero."}) end},
  }, 

  ["meta"] = {
  _config = {onspawn = function(player) vRPclient.notify(player,{"Eres un metero."}) end},
  }, 

  ["coke"] = {
  _config = {onspawn = function(player) vRPclient.notify(player,{"Eres un puto cocainomano"}) end},
  }, 
  ["motero"] = {
  _config = {onspawn = function(player) vRPclient.notify(player,{"Eres un motero."}) end},
  }, 
  ```
  
  marihuana >> allows weed entrance
  blanqueo >> money laundering
  meta >> meth lab
  coke >> coke lab
  motero >> biker clubhouse
  
    ```
    The coords for everything is in warehouses.lua
    It's all commented there, coords and shit.

·    Screenshots

https://cdn.discordapp.com/attachments/357969855523192834/389485760522223626/unknown.png
https://cdn.discordapp.com/attachments/357969855523192834/389485869918322688/unknown.png
