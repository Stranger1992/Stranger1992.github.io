Below you will find the existing and NEW Object Code Bits (OCB) for objects. 

Any specific levels where an entity exists once (ie: the famous Midas gold effect) have their original data file listed as ``` xxx. extension ``` . 

All objects will be listed in their original slots and their TEN slots for ease with TEN on the top and the original slot underneath. Feel free to click on the ID name to download a fixed version of the entity for use in TEN.

**Please note that these OCB values are for Tomb Engine ONLY.**

# Generic 
#### ```Switch_Type X```

  - 0 for wall switch
  - 1 for small wall switch
  - 2 for small button
  - 3 for big button
  - 4 for giant button (sequence switch)
  - 5 for valve turn
  - 6 for hole switch
  - any other OCBs play corresponding switch on anim or OCB+1 switch off anim.

#### Crowbar out of wall animation + pickup

- put OCB 9 to perform lara's animation of pulling crowbar out of wall + crowbar pickup. (works with TR5 wall crowbar from The Submarine level)

# Tomb Raider : Starring Lara Croft

#### ```ID_WINGED_MUMMY```

*  1 - Start off flying when triggered.
*  2 - Start off as a mummy when triggered.
*  4 - Start posed.
*  8 - No Wings.
*  16 - Disable Bomb Attack.
*  32 - Disable Shard Attack.

# Tomb Raider II: The Dagger of Xian.

# Tomb Raider III: Adventures of Lara Croft.

#### ```ID_COBRA```

* To correct the death animation: please change the ```STATE ID``` of ```ANIMATION 5: "COBRA_ANIM_DEATH" ``` from ```0``` to ```4``` 


# Tomb Raider IV: The Last Revelation.

#### ```ID_ROLLINGBALL```
* 1 - Rollingball silent mode - No camera shake or sound.

#### ```ID_TEETH_SPIKES```

* 0 -  Ordinary TR4 teeth spikes behaviour
* 1 - Spikes stuck out constantly
* 2 - Stick out once and retract forever
* 3 and onwards - OCB specifies spikes retraction delay in frames, i.e. OCB 30 = spikes will delay for 1 second, OCB 60 = 2 seconds, etc

#### ```ID_HAMMER``` ```Hall.TR4```

* 0 - Does not animate but will cause Lara damage if collided.
* 2 - Hardcoded Obelisk set up.
* 3 - Triggers once, then raises up and remains there. 
* 4 - Works like OCB 3 but will not stop. So once triggered will continuously raise, smackdown, raise up and then loop every two seconds.

#### ```ID_DOG```

* 0: Normal behaviour
* 1: Starts frozen (laying down like statues). Trigger to wake them up.

#### ```ID_WATERFALLMIST```

* OCB ```xxyy``` where XX is width, and YY is sprite size.

# Tomb Raider Chronicles

#### ```ID_BOMB```

* Add  0-99 to OCB for delay (quarter seconds) 
* Add 10000 to OCB for green explosion  ( 0 or 1) 
* Add 100-900 to OCB for size  (1-9)
* Add 1000 to OCB for blast wave ( 0 or 1) 

#### ```ID_GUARD1``` ```ID_SWAT``` ```ID_SWAT_PLUS``` 
```(ID_GUARD1)(ID_GUARD2)(ID_GUARD3)```

* 0 - Default.
* 1 - Reload
* 2 - Door Kick
* 3 - Rappel Down Rope
* 4 - Sleeping
* 5 - Rappel Down Rope (Fast)
* 6 - Wait On Wall
* 7 - Use Computer
* 8 - Start Hunt Stop
* 9 - Use Computer Scientist
* 10 - Idle
* 11 - Run

#### ```ID_HITMAN```
```ID_CYBORG```

* Set room type to "No Lens Flare" and he will choke to death.
