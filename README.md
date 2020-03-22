# cod4lvl55 - Modernised
##level 55, all weapons, challenges (only weapon challenges), etc.

**want to be max level like literally 99.99% of the entire Cod4 playerbase but all the guides are ages old,
the guides are on patch 1.7,
if there is a 1.8 patch guide, it's for non-steam and not using Cod4x,
or you're just that lazy like me?**
i got you. a modern drag and drop profile to use for Cod4x 1.8, both non-steam and steam. i personally use steam cod4x 1.8.

##instructions:
1. clone this repo to get the mpdata file.
2. drag and drop the mpdata you downloaded into `Call of Duty 4 directory\players\profiles\YOURNAMEHERE\mpdata`
3. slap ass in 2k20

I have not tested if Cod4x adds any extra data such as a GUID or something to mpdatas. I only modernised this by doing some hacky things with the 1.7 mpdata that is commonly found on shitty youtube videos you see for level 55. 
as i said, i play on Steam Cod4x 1.8 latest version with this exact profile so not only this should work with no problem, but you will need to modify things to suit you such as name and classes.

**YOU CAN NOT USE A 1.7 MPDATA FILE ON 1.8! THIS IS THE REASON FOR FAILURE TO READ MULTIPLAYER DATA, YOUR STATS HAVE BEEN RESET.** my mpdata should solve this problem.

# extra things

## coloured name in scoreboard on servers using steam:

change your steam name with the colour codes you want. 

e.g. `^6Alastor`

For servers that don't use steam name (garbage servers that you can probably cheat on easily.), change the name in Multiplayer Options.

## coloured profile name
literally change your profile folder in `Cod4\players\profiles\YOURNAME` to the colour codes. e.g. `^6Alastor`

You can colour just about any string in cod4 with the colour codes.

# best network settings to reduce hitmarkers/no hit reg e1?!?1/1/  bro?pls
you're just shit. if you think otherwise, get better internet and put these into your `config_mp.cfg` in your profile:
```
seta com_maxfps "9000" // quake 3 engine (hence iw3mp). frame rate matters a lot. if you play at 20 fps, expect shit gameplay. also expect to be literally unhittable due to model skipping for others so you'll probably get kicked for being unhittable.
seta cl_maxpackets "125" // servers typically cap it at 100 so might be better off using 100. 
seta cl_packetdup "3" // only use 3 if you got a lot of bandwidth. more duplicated packets just waste bandwidth but im rich so fuck your 256kbps modem. also use if you have a lot of packet loss. bruh use ethernet
seta cl_timenudge "-10" // this gets thrown around a lot by retards who think you can change interpolation on the client side. honestly i don't see this command anywhere to exist so use if you want to idc 
seta rate "100000" // only use this value if you dont play on shit servers that cap your maxrate and if you even have 100kbps+ bandwidth also including the cl_packetdup value. shit internet speeds use 25k (25000)
```

# colour codes
^0 = Black

^1 = Red

^2 = Lime Green

^3 = Yellow

^4 = Navy Blue

^5 = Light Blue/Cyan

^6 = Pink/Purple

^7 = White/Default

^8 = Gray

^9 = Gray/Map Default
