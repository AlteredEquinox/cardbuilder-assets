# Altered Card builder assets export

This repository contains all the graphical files to be used in a card builder for the Altered TCG.

## Icons

The fonts provided here are free to use. Other fonts like Haptic Pro and Jalli Greek cannot be included due to license restrictions.

## Frames

The Frames files are specific for each faction, rarity and text volume.

As general rule : 

-	T1: small text with echo
-	T2: large text with echo
-	T3: small text without echo
-	T4: large text without echo

The specific rules are:

For CHARACTER, SPELL and PERMANENT:
-	If they are COMMON or RARE and they have an echo effect: T1
-	If they are COMMON or RARE and they do not have an echo effect: T3
-	If they are UNIQUE and they have an echo effect: T2
-	If they are UNIQUE and they do not have an echo effect: T4

For TOKEN and HERO:
-	T1 only

## Icons

Theses visuals are specific to each and each rarity. They are to be placed on top of the corresponding frame.


## Attributes

Attributes files are to be used depending on the values of the attributes for the card using the following rules : 

There are three sizes: Large, Medium, Small (plus a special transparent Small for 0)

Look at each stat and check :
- if it's 0, use the special 0 visual.
- if it's strictly below the other two stats, use Small.
- if it's strictly above the other two stats AND at least one of them is different from 0, use Large.
- in any other cases, use Medium.

Some examples:

5/5/6
5: is not 0, is neither strictly below or above the others -> Medium
5: is not 0, is neither strictly below or above the others -> Medium
6: is not 0, is strictly above the others and at least one of them is different from 0 -> Large

3/0/2
3: is not 0, is strictly above the others and at least one of them is different from 0 -> Large
0: is 0 -> transparent Small
2: is not 0, is neither strictly below or above the others -> Medium

0/0/5
0: is 0 -> transparent Small
0: is 0 -> transparent Small
5: is not 0, is strictly above the others but none of them are different from 0 -> Medium

2/2/1
2: is not 0, is neither strictly below or above the others -> Medium
2: is not 0, is neither strictly below or above the others -> Medium
1: is not 0, is strictly below the others -> Small

3/0/3
3: is not 0, is neither strictly below or above the others -> Medium
0: is 0 -> transparent Small
3: is not 0, is neither strictly below or above the others -> Medium

5/7/6
5: is not 0, is strictly below the others -> Small
7: is not 0, is strictly above the others -> Large
6: is not 0, is neither strictly below or above the others -> Medium

## Illustration

These files are the background image to be used according to card reference and the text boxes chosen in the Frames section.

These files trademark line will be masked when using the Frame visual over it.

