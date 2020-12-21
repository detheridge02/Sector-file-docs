# /Airports/EGxx/SMR/Labels.txt
# What are they?
Labels are the text on SMRs - labeling holding points, taxiways, and/or stands. Generally all stands and holding points should be labeled, although taxiways are optional.

# What do they look like in EuroScope? 
![enter image description here](https://user-images.githubusercontent.com/14115426/101296592-23745b80-381c-11eb-85a0-df5a806b78f7.png)

In this image, all the pieces of text ('27,''28''24','N1','Z1','B1','A2','A3','A1','M3','M1') are labels.

They are generally all enabled in SMR PRFs and ASRs but if they aren't, they can be enabled by:
Other Set -> Display settings-> Freetext (expanded) -> Tick SCT2
![enter image description here](https://user-images.githubusercontent.com/14115426/101296793-5c610000-381d-11eb-8187-841a3563523e.png)

# How to format them
They go into the .SCT file.

    "[Label text]" [LAT coordinate] [LONG coordinate] [colour]
   E.g.

    "A1" N051.09.08.328 W000.10.02.181 standHold
Further examples can be found in [/Airports/EGKK/SMR/Labels.txt](https://github.com/VATSIM-UK/UK-Sector-File/blob/master/Airports/EGKK/SMR/Labels.txt).

The coordinates follow standard EuroScope coordinate formatting.
The colour follows standard EuroScope colour formatting.

# Where to find them?
Generally, labels can be found by searching the .SCT file for (without the quotes): 
'; Start [airport name] [ICAO] Labels'  or similar.
E.g. '; Start Gatwick (EGKK) Labels'

# Reference
Reference documentation can be found in the [VRC wiki](http://www1.metacraft.com/VRC/docs/doc.php?page=appendix_f).