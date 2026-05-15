## Map Sprites

I'll be including a lot of "fix for LT" assets here. These are simply redone for LT to support the ability to import them into Lex Talionis.

Assets from the FE-Repo can be imported into FEGBA fine but fail importing into LT. The most common reason is due to height differences. This particular issue has been fixed, as now 488 px tall walk sprites can be imported. However, I will still include other minor fixes I have made in this repository.

I may make fixes for palettes where needed as well, so when imported in LT it will properly generate gray variants.


### Lords

#### Svetlanya

Custom sprite design for my OC, Svetlanya. She's classified as a Mage Lord to match FE Essentials naming conventions, but her class in my scenario is "Lady" instead.

Svetlanya is a Water Elf and I wanted a cute pose where she's holding a hand to her chest and staring up into the sky. I'm unhappy with her "Cast" pose and will probably redo it later.

This is a FULLY CUSTOM SPRITE, not an edit. It is based on the FE style of course, I was intentionally recreating the style of FE sprites while doing my own thing.

I haven't finished the Sword Walk design yet.

- Class: Mage Lord
- Original: Svetlanya
    - by JaidynReiman
    - OGA-BY 3.0+, F2E, F2U
    - Body Types: Female
    - Weapon: Unarmed, Sword
    - Poses:
        - Stand: Svetlanya
        - Walk: Svetlanya

#### Svetlanya Forward

My original design of Svetlanya's sprite before I changed the pose. I think this should still work with her correct walk animations.

I abandoned this design because I just don't like it as much, but I'm leaving it open for anyone to use if they want. I did use this pose to help with her walk animation.

- Class: Mage Lord
- Original: Svetlanya Forward
    - by JaidynReiman
    - OGA-BY 3.0+, F2E, F2U
    - Body Types: Female
    - Weapon: Unarmed, Sword
    - Poses:
        - Stand: Svetlanya Forward, Svetlanya Forward Alt
        - Walk: Svetlanya

#### Generic Mage Lord

This is just Svetlanya's design without her non-human physical attributes, making her "generic". This is designed for people who like the sprite and just want to use her.

No Move animation exists _yet_, but I will create one later. Its not that hard, but I have to make some minor alterations to make it work. A better variant would probably be not making her hair white either so she's truly "generic".

Until a Generic Move is made, just use Svetlanya's move animation.

- Class: Mage Lord
- Original: Generic
    - by JaidynReiman
    - OGA-BY 3.0+, F2E, F2U
    - Body Types: Female
    - Weapon: Unarmed, Sword
    - Poses:
        - Stand: Generic
        - Walk: Svetlanya


#### Elf Lord

This was originally made in my Legacy assets and was edited directly off of OG Eirika's sprite. It was originally designed for Amaya, and I plan to keep using it tentatively for her for now.

- Class: Lord
- Original: Eirika
    - by IS
- Edit: Elf
    - by JaidynReiman
    - F2E, F2U
    - Body Types: Female
    - Weapon: Sword
    - Poses:
        - Stand: Elf
        - Walk: Elf


#### Mage Lord Elf

This is a super minor edit of TyTheBub's "Mage Lord" to add elf-style ears. Originally I planned to do a more advanced edit later, but now I just plan to make customs instead.

- Class: Mage Lord
- Original: Eliwood
    - by IS
    - Body Types: Male
- Edit: Mage Lord
    - by TyTheBub
    - Body Types: Male, Female
- Edit: Elf
    - by JaidynReiman
    - F2E, F2U
    - Body Types: Male, Female
    - Weapon: Sword
    - Poses:
        - Stand: Elf
        - Walk: Elf


### Mounted

#### Wolf Knight

There wasn't any Wolf Knight map sprites, so I made one! I really liked the Wolf Knight concept and just had to figure out how the pose should go.

What I did here was I took the Nomad sprite edits by Leif and merged them into VelvetKitsune's Wolf sprite to create Wolf Knight.

- Class: Wolf Knight
- Original: Mouthe Dauge, Nomad
    - by IS
    - Body Types: Monster, Male, Female
- Edit: Wolf
    - by VelvetKitsune
    - Body Types: Monster
- Edit: Nomad Dagger
    - by Leif
    - Body Types: Male, Female
- Splice:
    - by JaidynReiman
    - Spliced Assets: Wolf, Nomad Dagger
    - F2E, F2U
    - Body Types: Male, Female
    - Weapon: Dagger
    - Poses:
        - Stand (Mounted): Wolf Knight
        - Walk: Wolf Knight


### LT Fixes

This is just for quick fixes so sprites can import into Lex Talionis. I take no real credit for them.

#### Lords

- Noble (M) Launch T1 {VelvetKitsune}
- Successor (M) Launch T2 {VelvetKitsune}

#### Dancers

Dancers have received special formating to put back together the animations and place it in a standard LT sheet. We still haven't figured out how to animate these assets yet, but I did at least parse out the walk/move as well so they can be dropped right into LT.

- Dancer (F) {Circleseverywhere}
- Dancer (F) Larum {IS}
- Dancer (F) Larum Long Hair {Momo}
- Dancer (F) Ninian {IS}
- Dancer (M) FE8-Style {L95}
- Muse_Gypsy (F) {Alexplode}


### Legacy Map Sprites

These map sprites were made by me when I was looking into potentially doing Fire Emblem XP over a decade ago. That project was abandoned, but I still had these assets lying around.

I have only kept the ones with notable changes. I haven't yet adapted these for FEGBA or Lex Talionis, but eventually I would like to.

- Female Berserker
    - Female Berserker already exists now, but this was a simple edit to add a chest band for obvious reasons.
- Dark Mage w/Bangs
    - For an OC named Trent. Some exist like this, but this exact design does not.
- Hatless Mage?
    - I can't remember the exact purpose, but I assume it was removing the hat. Probably not that special given this already exists.
- Demon Swordmaster
    - I was working on fully repaletting this one but never finished. The sprite has horns in addition to a (partially converted) black kimono.
- Headbandless Female Thief
    - I actually really like this one, it looks pretty unique.
    - For an OC called Melody. While she won't be using this sprite I still like the design. Its not like other long-haired thief sprites such as Legault.
- Female Assassin
    - Honestly doesn't look very good, probably not worth porting over.
- Pegasus Staff
    - I suspect this does exist, but I'll compare it anyway and see if its worth porting.
- Peg Leg Pirate
    - This character was created as a joke mostly. I do like the Peg Leg though and may port it over.
- Sword Cavalier
    - Is a lie, because I don't see a sword there. I'll compare it to other sprites but I doubt this is anything interesting.
- Hat Archer
    - Archer with a hat. Based on a rough concept I did a while back.