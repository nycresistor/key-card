# Resistor Key Card Holder

This is a credit card sized key holder for the two types of keys used to unlock the doors to Resistor. 

To use, simply press fit each key into its corresponding key profile; it should be friction fit and hold on without issue. To remove a key, either use the finger scoops at the end of each key blade to lift the keys up and out, or if you printed it in a flexible material like TPU then flex it out. 

![](keycard.png "An image of the key holder, with an old, not-Resistor key resting inside it. The key bitting has been censored. This particular iteration of the print has a tiny bit of damage in the empty key profile, but this doesn't matter because I'm simply the one designing the key card holder and (at least as of writing this document) don't yet have keys of my own to use with it. It's probably best to reprint it properly if you are going to actually use it.")

## Printing

[**Go here and hit "Download Raw File"**](/Resistor%20Keycard.stl)

The only prerequisite to print is that the layer height is set to 0.2mm or lower (by default). The thin card base benefits greatly from having two layers or more for strength. In terms of material choice, anything should be fine. The initial Craft Night prototypes were done in TPU and worked well enough, but all of the following versions were tested in both PLA and PETG. 

## Modifying

This model was designed in Fusion, which can be accessed using the Fusion archive file. Many aspects of the model, such as the card thickness, are defined as parameters and can be freely adjusted for quick edits. I'd like to think that each parameter is named obviously enough to be of use. 

The bow of the Kwikset key is a bit of an anomaly in that regard, given that the holes for it were modeled by projecting a known good blank's profile into a sketch and tweaked manually. In practical terms, this means that the `kwikset_hole_tolerance` parameter can't easily be set above 0.2mm currently because otherwise Fusion freaks out. I'm hoping to address this in the near future. 
