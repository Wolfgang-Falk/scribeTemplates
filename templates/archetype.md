```
watermark (
Pathfinder 2E — Archetype Template
)
title ( 
    Archetype Name
)
<!-- The header text; The "(())" is for your TOC -->
head (
# Archetype Name ((Archetype Name))   
An epic description for the archetype
-
)

An archetype description worthy of the roleplay!

<!-- Column break -->
|


/

<!-- Standard HTML elements also work --->
##### <span style="display:inline;font-family:'linotype-sabon'!important;font-size:12px;text-transform:capitalize;">Additional Feats ((+Additional Feats)) <span style="font-weight:normal">**Xth:** additional feat name (*Core Rulebook*, p. 00)</span></span>

<!-- You can have feats with normal headers or use the specialfeat element with item -->
<!-- Tags require the ";" at the beginning of the list with commas as delimiters -->
specialfeat {
item (
# Archetype Dedication ((+Dedication))
## Feat 2
-
;uncommon,rare,archetype,dedication
**Prerequisites** Necessities
-
You gain the thing.

**Special** You cannot select another dedication feat until you have gained two other feats from the [archetype name] archetype. 
)
}

specialfeat {
item (
# Feat Name  ((+Feat Name))
## Feat 4
-
;archetype, focus spell
**Prerequisites** archetype dedication
-
You gain the *spell name* focus spell, and you increase the number of Focus Points in your focus pool by 1. 
)
}

|

<!-- this div helps with adjusting feats to not have a gap from the description seperation -->
<div style="margin-top: -10px">

specialfeat {
item (
<span style="font-size: 18px;font-weight:bold;text-transform:uppercase;font-family:'ff-good-web-pro-condensed'!important">Feat Name</span> 
## Feat 4 ((+Feat Name))
-
;archetype, skill
**Prerequisites** archetype dedication 
-
Feats Description
)
}

</div>

<!-- Next Page -->
=


|

# Focus Spells ((Focus Spells))

item(
# Focus Spell Name ((+Focus Spell Name))
## Focus X
-
; uncommon,rare, abjuration, concentrate, focus spell
**Casting** :a: :aa: :aaa: somatic, verbal, material

**Range** Touch; **Targets** One creature

**Duration** Sustain up to 1 minute
-
You cast the thing
-
**Heightened (+1)** The thing is better!
)

=
```
