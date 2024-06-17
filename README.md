# MS20-Filter-1U

 MS20 Filter made with Rene Schmitz's Design in Intellijel 1U format

**<Note> This built has not been built or tested yet, use as reference only, and to your own risk.**

Rev.0.1 - Initial build

|Process|Status|Time|
|-------|------|----|
|PCB|Drawn|6/12/2024|
|Fabrication|Done|6/15/2024|
|Build|Done|6/16/2024|
|Testing|Not Started|Est. Starting Time: 6/21/2024|

Issues:
- Panel is too high (please don't use it. It does not fit.) (Fixed. It should work now (untested))
- I used bc557 transistors instead of 2n3906s because they are substitutes and it didn't work. Later, I found out their pinout is opposite (2n3906: EBC, bc557: CBE) so it isn't working now and I have to wait one week to retest it (Because of school) ;(. Moral of the story?  **Always check component datasheet before replacement!**
- Just now I checked again, and realized I actually used bc558 transistors!!! For the whole time I thought I was using bc557... But I checked it as well and it should be compatible as long as it is connected the other way round, but I have both and it seems 557 is a better alternative than 558.
- One 470K Resistor is wrongly marked as 220R on the PCB (Fixed in the original file)
- One 4.7K Resistor isn't present (I forgot to put it on) but should not affect normal usage a lot... (I will be sure to add it in the next revision.) (nevermind it's fixed)
