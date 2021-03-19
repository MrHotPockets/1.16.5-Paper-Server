Paper Version: 1.16.5-556.jar
By running this server you agree to the minecraft EULA

CAUTION
-If you plan on using additional plugins, go to the to the paper.yml file in the directory and set hopper.disable-move-event to false. This usually breaks plugins that uses the event, typically for any plugin that has some sort of protection against greifing
-Don't use redstone algorithm plguins for optimization: redstone is already optimized in the paper.yml. If you have to though set use-faster-eigencraft-redstone to false in the paper.yml. 
Note this heavily affects performance (This setting reduces redundant redstone updates by as much as 95% without breaking vanilla devices. Empirical testing shows a speedup by as much as 10x!)
-The view distance by default is set to 10. This is the most demanding setting, thus you can set it lower for optimization. 6-8 is recommend for survival. If you want to go lower though, 
set mob-spawn-range in the spigot.yml to 1 below that value (ex. If view-distance is 5, set mob-spawn-range to 4)


Server Info and Tips or smth
If you're doing an event of some sort please do it at least 2 hours prior as you might run to some issues
To change to amount of RAM use this site to convert GB to MB 
https://www.gbmb.org/gb-to-mb
Replace to Xms and Xmx value at the beginning (Should be 5120M by default) with the binary MB value result (For instance 8GB would be 8192MB or 8192M)
The default value (5GB) should be able to handle up to 10 players
If you want to pre-gen a server then do it the day before. 
The server does not save user data on crash, and instead only when the server is stopped/restarted. It instead backsup the server every 5 mintues for optimization purposes. You can change the amount of time it takes in the bukkit.yml.
Some settings, such as tick-inactive-villagers, are left on default to still maintain a true vanilla experience. You may further optimize if you are lagging, though beware some setting might be dangrous or disable features or
ticks 



Here are a few settings that are important. Best to leave at default though if you like you can change these
Paper.YML:
max-auto-save-chunks-per-tick: 6
Slows down incremental chunk saving. Greatly reduces lag reduction. The guide says 6 but you can go to 8 to be 100% sure chunks are saved


Server World Info:
5000x5000 area is pregenerated
It is meant for survival purposes

Server IP Setup:
Port Forwarding: https://www.youtube.com/watch?v=pSEhgCp5UBk
If you want to prevent others from having to use your IP address then make a domain/ custom IP: https://youtu.be/L6lgVGuXDZs
If you want to prevent others from possibly finding your IP and DDOSing you when the server is up you can use TCPShield: https://www.youtube.com/watch?v=mJHgbR6hK3A

Links and Credit:
Optimization (Up-to-date): https://www.spigotmc.org/threads/guide-server-optimization%E2%9A%A1.283181/?__cf_chl_jschl_tk__=c95a1ccadc9beab6e813d45ff016dee3c50b0aea-1616135214-0-AZAgf-hE4BCBbysy4cJi1KLvB8gknqzqiTGHVEM0Uc3CXe3cDW6gNhJgkRg_3Uo1HbP2N7PKhxJ-G18Gr8Hg62TuugyD0S9JlkWt2GU1H_OH79E_eELgm8pIaUnPOXMegextjztnyktMbHlsgDTKWBf5XQquU72PQhw0QrT9YJkbgjfVoaxKW-3rTosQgAjbqojAA2LjOtV_n_wBYhlBCrDn-U9ZUi7dlXhRgv5JJI6Rr5DoP7_LSnEng9uhej3vZP94cETK-TSBhji4NHhgy4BpioYCIEyfITNGuPwqx4XmXVnKcfDFZytwSi4BxnaElxxuLNfpVRMJgOXV3XlEKbJqA_3Gt0UWN_sYx9CNjPLJmy_A3FtNkdQRAMxpHjNEoBXM8a5scZbpziCwalTX5ho
Pre-Gen: https://www.spigotmc.org/resources/fast-chunk-pregenerator.74429/



It is recommended to pre-gen the world, though the server already comes with one.

Server Commands:
In the server console you can run commands without using /
To stop the server do /stop
To op someone do /op
To deop someone do /deop