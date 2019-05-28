# Different Starting Strands Experiment
Written by Harshu Musunuri, 5/10/19, *Performed:* TBD

Procedure Purpose
=================

Test backspace method on different starting strands from BS_Start to characterize effects of potential secondary structures on binding between extended strand and complementary strand to prevent cutback on dsDNA. 

Overview
========
In order to conduct DNA synthesis using water-soluble and non-toxic materials, a method using a pair of enzymes to extend and shorten a pre-existing template strand has been devised and termed the 'backspace' method. This technique involves three steps:

1. Elongating an existing single-stranded DNA strand with an arbitrary length of one nucleotide of choice using Terminal Deoxynucleotidyl Transferase (TdT).
2. Adding a complementary strand that matches the 3' end of the original starting sequence, as well as one or two of the added nucleotides.
3. Introducing Exonuclease T, which will cleave the 3' region of the elongated starting strand, effectively cleaving excess nucleotides that are not to be added. (zuo_deutscher_1999)
This experiment is intended to implement each of the steps of the 'backspace' technique, resulting in the addition of a single nucleotide to a pre-determined ssDNA strand. The protocol builds on previous experiments undertaken using TdT and Exonuclease T. 

TdT extension and ExoT cutback will be tested on both the original and the modified starting strands, each with 2 different complementary strands (of 5 and 6 bp lengths). 

## Materials

-   100 uM "BS_Start" Oligonucleotide- Original (Sequence: 5'-AGTTACCATGACCGTGTGCG-3')
-   100 uM "BS_Start_PosControl" - Original (Sequence: 5'-AGTTACCATGACCGTGTGCGT-3')
-   100 uM “BS_Comp_6” Complementary Oligo (Sequence:  5’-AACGCA-3’)
-   100 uM "BS_Comp_5" Complementary Oligo (Sequence: 5'-ACGCA-3')
-   100 uM "BS_Start_Mod" Oligonucleotide  (Sequence: 5'-AGTTACCATGACATTGTGC-3')
-   100 uM "BS_Start_Mod_Comp6" Complementary Oligo (Sequence: 5'-AAGCAC-3')
-   100 uM "BS_Start_Mod_Comp5" Complementary Oligo (Sequence: 5'-AGCAC-3')
-   10/60 Ladder 
-   Terminal Deoxynucleotidyl Transferase (20 U/uL)
-   Exonuclease T (5 U/uL)
-   dTTP (100 mM)
-   NEB TdT Buffer (5X)
-   TBE Buffer (0.5X) 
-   CoCl2 (10x)
-   RNAse Free Water
-   500 mM EDTA

## Dilutions
1. Dilute 1.92 uL of BSStart (100uM, 6133Da) in 28.08 uL of nuclease-free water for 30 uL of a 6.4 uM solution. Vortex well. Do the same for BS_Start_Modified. Store separately. 
2. Dilute 3 uL of 100 uM dTTP in 27 uL of nuclease free water for 30 uL of a 10 mM working stock. 
3. Dilute 0.96 uL of 100 uM BS_Comp_6 in 14.04 uL of nuclease free water for 15 uL of a 6.4 uM working stock. Repeat for BS_Comp_5, BS_Start_Mod_Comp6, and BS_Start_Mod_Comp5. 

Samples
=========
Number of sample corresponds to the lane in which it will be placed in the gel: 
1. Ladder
2. BS_Start Original (Extension Control)
3. BS_Start_Modified (Extension Control)
4. BS_Start Original (Negative Control)
5. BS_Start Original with BS_Start_Comp_5
6. BS_Start Original with BS_Start_Comp_6
7. BS_Start_PosControl
8. BS_Start_Mod (Negative Control)
9. BS_Start_Mod with BS_Start_Mod_Comp5
10. BS_Start_Mod with BS_Start_Mod_Comp6
11. BS_Start_Mod (Negative Control)
12. Ladder 

These samples will be each be prepared separately by 2 people for technical replicates (2 identical gels will be run at same time).

Procedure
=========

## TdT Extension Reaction
1. Set one thermocycler to incubate at 37C for 10 minutes, 90C for ten minutes, then hold at 4C. This experiment is designed to have one batch of extension products for each starting strand, in order to reduce extended sample variability. 
2. Pipette 22.8 uL of water, 6 uL of 10x TdT Buffer, and 6 uL 10x CoCl2 into 2 PCR tubes. 
3. Add 12 uL of ~40 ng/uL 'BS_Start' into PCR tube 1, and 12 uL of 'BS_Start_modified" into PCR tube 2.  
4. Pipette 12 uL of 10 mM 'dTTP dilute' into both tubes, and place in thermocycler. 
5. Immediately before starting the protocol, add 1.2 uL of 20 U/uL TdT to both tubes. 
6. Boil both tubes at 90 C to deactivate TdT before comp strand binding step in thermocycler. 
7. Transfer 20 uL from tube 1, into tube labeled "Original Extension Control", and another 20 uL into a tube labeled "Original Comp5". The remaining will be used for "Original Comp6". 
8. Transfer 20 uL from tube 2, into tube labeled "Mod Extension Control", and another 20 uL into a tube labeled "Mod Comp5". The remaining will be used for "Mod Comp6". 

## Complementary DNA Binding 

NOTE: It is critical that the entirety of the Exonuclease T reaction takes place at the appro-priate temperature.  
All addition of Exonuclease T must occur while the sample is inside thethermocycler while being kept at the correct temperature.

1.  Add 6μL of dilute ‘BS_Comp_5"to tube 5. 
2.  Add 6μL of dilute ‘BS_Comp_6"to tube 6. 
3.  Add 6μL of dilute 'BS_Start_Mod1_Comp5' to tube 9. 
4.  Add 6μL of dilute 'BS_Start_Mod1_Comp6' to tube 10. 
5.  Add 1μL TdT buffer and 1.4μL of water to each of the 4 tubes and mix thoroughly.
6.  Set one thermocycler, Thermocycler 1, to hold at 94◦C for two minutes, then lower the temperatureto 0◦C forever (decreasing at 0.5◦C per second). Place all sample tubes into Thermocycler 1 and start the protocol.
7.  Set another thermocycler, Thermocycler 2, to hold at 94◦C forever and start the protocol.
8.  Keep the tubes in the thermocycler for the remainder of the experiment.

## Exoncuclease T Cleavage

1. While the validation test samples are held in the thermocycler at the appropriate temperature, add 1.6μL of Exonuclease T to each sample.
2. After one hour of Exonuclease T incubation, rapidly transfer the four tubes to thermocycler.
3. Allow to heat inactivate for at least ten minutes. Avoid touching the inside of the thermocycler.
4. Add 5 uL of 500 mM EDTA to each well. 

## Gel Setup 

1.  Remove two 20% polyacrylamide gels from pouches and rinse with deionized water.
2.  Peel off tape on bottom of 20% polyacrylamide gels and remove combs.
3.  Lower  the  Buffer  Core  (the  piece  that  holds  the  gels)  into  the  Lower  Buffer  Chamber  so  that  thenegative electrode fits into the opening in the gold plate.
4.  Insert the Gel Tension Wedge into the XCell Surelock behind the buffer core. Make sure it is in its‘unlocked’ position, which allows the wedge to slip into the unit.
5.  Insert gel cassettes into the lower buffer chamber.  The shorter “well” side of the cassette faces intothe buffer core.  The slot on the back must face outward.  If only one gel is being run, insert a bufferdam in the place of a gel cassette.
6.  Pull forward on the Gel Tension Lever toward the buffer core until the gel cassettes are snug againstthe buffer core.  This puts it in the ’locked’ position.
7.  Fill the Upper Buffer Chamber (between the gels) with running buffer.  Ensure it is not leaking.
8.  Fill the Lower Buffer Chamber completely with running buffer by pouring TBE next to the Gel TensionWedge.
9.  Pipette 12μL of running buffer into each gel well.
10.  Place the gel cover on the apparatus in the correct orientation.  Connect the electrodes to the powersource, and pre-run the gel for 30 min at 150 V. 

## Gel Loading/ Running

1.  Obtain small gel running tubes. Pipette  5μL  of  2x  Gel  Loading  Buffer  II  into each well of two rows of these tubes. 
2.  For  the  ladder  well,  load  4μL  of  .5X  TBE  Buffer  into  the  already  present  5μL  Loading  Buffer  II droplets.  Load 1μL of 10/60 Ladder, and mix well by pipetting upand down.
3.  For the remaining gel wells, load 5μL of the appropriate extension or test sample into the 5μL droplet of Gel Loading Buffer II (contains 18 mM EDTA), mix well, and then load 5μL of the mixture directlyinto the appropriate gel well. This should result in approximately 30 ng/lane on a gel (depending on the sample) which is within the target of 20-40 ng per lane.
4.  Run the gels at 150 V until the dark blue dye is three quarters of the way to the bottom of the gel.  If the dark blue dye is not visible, run the gel for three hours.
5. While the gel runs, prepare 1X SYBR Gold Staining Solution with TBE as dilute.
6.  Once gel has finished running, submerge gel in SYBR Gold solution for 20 minutes.

## Experimental Updates
- First set of samples rendered unusable due to addition of ExoT prior to annealing thermocyler protocol for comp. strand binding, and tubes melting within thermocycler
- Second set of replicates made with separate TdT extended samples (procedure basically repeated)

## Results
![Gel Image](Original_vs_Mod.tif)

Gel buffer was not loaded fully to the top which created problems with voltage source when trying to run and resulted in hard-to-interpret readout. Reran samples on a different gel a week later. 
