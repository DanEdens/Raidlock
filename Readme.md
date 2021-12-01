# RaidLock - Clan Boss Data connection Toggle

This tool wraps Raid in a VPN that points at no where.  
This has the same effect as turning off your WIFI/Data, without you having to lose connection to other apps.   
This is partically useful if you play in Pop up window mode  

Todo: 
1. > Isolate components from Larger Raid toolkit
1. > Create standalone APK
1. > Create control notification and api endpoint for those without their own MQTT broker
1. > Query User to reestablish connection after run.
1. > search for Clanboss Logcat objects
1. > Adds Auto disable Net connection upon detecting Clan boss run
1. > add join endpoint 
1. > Alpha test
1. > Beta test
1. > Production releasei


The first is called "raidlock" and is a little pop up button (or notification buttons) for toggling Raid's data connection. 

I use this for 2 purposes. 
1. Start a clan boss and go AFK, With data disabled, You have a chance to throw out the run and retry. This doesn't prevent data reaching other apps on your phone like it does when you turn off mobile and wifi. 
2.  The first is that my PC version of Raid, tells my phone when it's running, so the phone doesn't disconnect me if i try to sign into 2 placecs at once. It locks Raid in a fake VPN that ONLY prevents Raid from communicating. 
