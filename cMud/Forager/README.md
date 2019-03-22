# Forager

Forager enhances the client experience with deciphering foraged foods and the ability to map rooms with color coded forage qualities.


### Prerequisites

cMud Pro 3.34

### Installing

Import the XML package.

![cMud Settings]( https://i.imgur.com/2mmz1rJ.png )

![cMud File]( https://i.imgur.com/L4jsr6a.png )

![cMud Import XML]( https://i.imgur.com/S5Fbva3.png )

![cMud Import XML]( https://i.imgur.com/sLsGzOg.png )

## Help File

Adds new local command to the client: **forager**

This is the primary help and control system for the forager class.  Typing forager without any arguments presents the help menu and current configuration parameters. 

![Forager]( https://i.imgur.com/TCyjnyz.png )


### General Info

Status value of 1 = On, 0 = Off.

#### Junker:
Junker enables you to configure foods you want to keep, or specify conditions you outright do not want.  

Conditions you add to the junk list (forager junk add effect) will always be junked no matter the other effects on the food.  

If the food does not contain any junk effects, it is inspected for effects listed under your keep effects.  
If a food does not have a junk effect, and does not have a keep effect, it is considered useless and junked.

Note: Special forage foods, good or bad, are not junked.  This includes *star shaped fruit, silver-leaf herbs, peaches, black-leaf herbs, etc*.

To see a mapping of food descriptions to effects type forager list.

