Catch all for scripts that don't go somewhere else
***********BardingBuffer***********
I got tired of applying these buffs manually and couldn't remember when I had applied them last. Now I hit a button and it applies disco, again for peace, again for provo. If I'm impatient and hit it before 10seconds instead of failing to apply it tells me to wait. Likewise if it hasn't been 5 minutes it'll let me know. (Timer is set to let you reapply at 4m30s)


***********CartogMapDecoder***********
Throw a ton of tmaps (lumber, ore, skin, fish good too) and spyglasses in your pack and this will take care of all of them. If you're not using a tome click your backpack or w/e container you want to put the completed maps into

***********Gate***********
Well annotated, you should be able to read it. Updated to send red/crim people to arena and blues to shelter.

***********HouseMacro***********
This macro is more complicated and takes some editing to get working perfectly. I took my time and put proper notes in to help you get there. Near the top add (with @ignoreobject) your friends/pets that are permagray and red so it doesn't target them. The doors part is the other difficult part. When a door is closed it has a different graphic than when it's open. The macro uses open doors, so you first need to get the graphic of your door(s) when they are open. The next thing you need to do is get the location (position in UOSteam) of the door when it's open. The reason you need to do that is because if I didn't put that check in it would open/close any door with the same graphic. If your doors face south you would change it to Y instead of X, for instance if @y found == 1234

***********ItemIDAutoSort***********
It will ID every item in 'FromBag' and then sort it either to 'SellBag' or 'KeepBag'. Keep bag is all the modifiers (invul, vanquishing, etc) you want to keep. I select my backpack as sellbag and generally just recycle items for arcane essences. If you're at 120 it'll do the whole bag at once and then click each item, otherwise it'll ID each item individually.

***********OverworldHotkey***********
Upon pressing the hotkey this will automatically skin corpses, shear sheep, turn wool into yarn, and turn yarn into bolts, and turns bolts into cloth. Pretty simple macro but I find it handy. It also pauses if a macro check comes up when harvesting.

***********RecallPurchaserDumb***********
Recalls around an entire runebook saying vendor buy. Make an agent called BuyMacro and load it with the items you want, get yourself to just barely overweight, throw regs into a bank/secure container, and make sure your last rune is the bank/courtyard.

***********ResearchMatsDecoder***********
Will decode an entire container of research materials. 
