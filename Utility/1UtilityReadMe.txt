Catch all for scripts that don't go somewhere else

***********CartogMapDecoder***********
Throw a ton of tmaps (lumber, ore, skin, fish good too) and spyglasses in your pack and this will take care of all of them. 

***********Gate***********
Well annotated, you should be able to read it. 

***********HouseMacro***********
This macro is more complicated and takes some editing to get working perfectly. I took my time and put proper notes in to help you get there. Near the top add (with @ignoreobject) your friends/pets that are permagray and red so it doesn't target them. The doors part is the other difficult part. When a door is closed it has a different graphic than when it's open. The macro uses open doors, so you first need to get the graphic of your door(s) when they are open. The next thing you need to do is get the location (position in UOSteam) of the door when it's open. The reason you need to do that is because if I didn't put that check in it would open/close any door with the same graphic. If your doors face south you would change it to Y instead of X, for instance if @y found == 1234

***********ItemIDAutoSort***********
It will ID every item in 'FromBag' and then sort it either to 'SellBag' or 'KeepBag'. Keep bag is all the modifiers (invul, vanquishing, etc) you want to keep. I select my backpack as sellbag and generally just recycle items for arcane essences. If you're at 120 it'll do the whole bag at once and then click each item, otherwise it'll ID each item individually.

***********OverworldHotkey***********
Upon pressing the hotkey this will automatically skin corpses, shear sheep, turn wool into yarn, and turn yarn into bolts, and turns bolts into cloth. Pretty simple macro but I find it handy. It also pauses if a macro check comes up when harvesting.
