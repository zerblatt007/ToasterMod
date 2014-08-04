ToasterMod
==========

A modification of my noname toasters 4060 based controller

I did not like the design flaws of it having problems if I change the burn time after the toaster was started. Sometimes it never stopped, and burned the toast.
I am also a big fan of indicators, and would like some feedback of how long time it is from releasing the toast. Ultimately I would like a 7-seg display for this, but the powersupply on the design will not work if we use too much current (It will not lock the el-magnet to hold the springs down and start the heater).
So a single LED was used, and works pretty ok.

![Finished mod](https://raw.githubusercontent.com/zerblatt007/ToasterMod/master/Images/top-mod.jpg)

I could have made a separate PSU unit, but the space inside the toaster is limited and the Toaster itself did not cost that much, so I just used parts I already had.

This has been posted to avrfreaks.net: http://www.avrfreaks.net/index.php?module=Freaks%20Academy&func=viewItem&item_type=project&item_id=1975

The source code is for the Atmel ATtiny15 written in assembly, but is very basic.
