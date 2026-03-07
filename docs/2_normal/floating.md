# Floating
This section covers floating.

## What is Floating?
Floating is when you perform the following:
While using FHS, hold down the Start button and turn the turntable.

When the game detects the above inputs, it will reset the GN to the number that you have originally set to when you turned on FHS.

This is super useful in soflan songs because you can always reset to the GN that you originally set to via floating.

For example, lets say you have set your GN to 300 and play a song with 100 BPM. If the song speeds up to 200 BPM, the GN will chagne to 150 (effectively making it twice as fast). If you float during the 200 BPM section, the GN will automatically correct itself to 300 (the saved value).

## Floating and WN
Unfortunately, for 99.9% of players, floating will change your WN. This is one of the things that you have to deal with if you want to play soflan songs at next level.

There are few things that you should consider in this regard:

- If you have enough time, hit the start x4 times instead of floating. This will turn off then turn on the SUDDEN+ which recalculates the GN*
- You can also try registering 2 turntable inputs (up -> down or vice versa) to minimize the amount of SUDDEN+ being moved
- Practice hitting minimal amount of input required to float

*The GN calculation happens when you turn off the SUDDEN+. While I may get more into it in the future, this bit is irrelevant for most of the soflan techniques covered on this site.

## Being bit more technical (can skip)
To explain the above in more technical sense, the game seems to do the following when the Start + turntable input is detected:

- Check the new WN based on the input
- Calculate the new Hi-Speed Value based on the new WN and the saved GN

This happens even when the WN value is not changed (i.e. having the SUDDEN+ set to the highest value, as mentioned above).