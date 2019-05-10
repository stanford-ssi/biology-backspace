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

TdT extension and ExoT cutback will be tested on both the original and the modified starting strands, each 

## Materials

-   100 uM "BS_Start" Oligonucleotide- Original (Sequence: 5'-AGTTACCATGACCGTGTGCG-3')
-   100 uM (*CHECK THIS CONC) “BS_Comp_6” Complementary Oligo (Sequence:  5’-AACGCA-3’)
-   100 uM (*CHECK THIS CONC) "BS_Comp_5" Complementary Oligo (Sequence: 5'-ACGCA-3')
-   100 uM "BS_Start_Modified" Oligonucleotide  (Sequence: 5'-AGTTACCATGACATTGTGC-3')
-   500 uM "BS_Start_Modified_Comp1" Complementary Oligo (Sequence: 5'-AAGCAC)
-   500 uM "BS_Start_Modified_Comp2" Complementary Oligo (Sequence: 5'-AGCAC)
-   10/60 Ladder 
-   Terminal Deoxynucleotidyl Transferase (20 U/uL)
-   Exonuclease T (5 U/uL)
-   dTTP (100 mM)
-   NEB Terminal Transferase Buffer (10X)
-   TBE Buffer (0.5X) 
-   CoCl2 (10x)
-   RNAse Free Water
-   EDTA (0.5M)

## Dilutions FIX DILUTIONS
1. Dilute 1 uL of BSStart (100uM, 6133Da) in 29.2 uL of nuclease-free water for 6.4 uM solution . Vortex well. Do the same for BS_Start_Modified. Store separately. 
2. Dilute 50uL 100mM dTTP Stock in 4950 uL water for 5000uL of 1mM working stock. Vortex well.
4. Dilute 4.32 uL of 90-mer (AGTATT ... TAGACGTT, 100uM, 27786Da), 13.04 uL of 15Mer (ATGGACATGGACTAC, 100uM, 4601Da) and 12.56 uL of BS_Comp_8 (AACGCACA, 100uM, 2388Da) into 3970.08 uL Nuclease-Free water in a 15 mL tube. Vortex well before use. This is the DNA Control Solution, which is 3 ng/uL 90mer, 1.5 ng/uL 15mer, and .75 ng/uL BS_Comp_8 working stock. This will result in 1.0ng/uL, 0.5ng/uL and 0.25ng/uL final concentrations of 90nt, 15nt and 8nt control stands in samples sent to PAN.
5. Dilute 7.82 uL of BS_Start_Mod1_Comp1 in 992.18 uL of nuclease-free water for 1 mL of 3.91 uM working stock.

Samples
=========
1. BS_Start Original with BS_Start_Comp_5
2. BS_Start Original with BS_Start_Comp_6
3. BS_Start_Modified with BS_Start_Mod1_Comp5
4. BS_Start_Modified with BS_Start_Mod1_Comp6
5. BS_Start Original (Extension Control)
6. BS_Start_Modified (Extension Control)
7. BS_Start Original (Negative Control)
8. BS_Start_Modified (Negative Control)
9. Ladder 

2 gels will be run with these samples (replicates). 

Procedure
=========

## TdT Extension Reaction
Set one thermocycler to incubate at 37\C{} for 10 minutes, 70'C for ten minutes, then hold at 4C.
Pipette 7.6 uL of water, 2 uL of 10x TdT Buffer, and 2 uL 10x CoCl2 into each of the PCR tubes.
Add 4 uL of 40 ng/uL 'BS_Start' into PCR tubes 1 and 2. 
Add 4 uL of 40 ng/uL 'BS_Start_modified" into PCR tubes 3 and 4. 
Pipette 4 uL of 10 mM 'dTTP dilute' into tubes 1 - 6. 
Place the 4 tubes in the thermocycler.
Immediately before starting the protocol, add .4 uL of 20 U/uL TdT to all tubes.
Start the thermocycler protocol and wait until the protocol is completed.
Transfer 10 uL from tubes 1 and 3 into a corresponding 

`Extension Control' tube for original and modified starting strands. 
Add 10 uL of EDTA to column 12 after all other wells have been inactivated/after inactivation of the shortest time reaction. 
**Note:** 1:11

## Complementary DNA Binding 

NOTE: It is critical that the entirety of the Exonuclease T reaction takes place at the appro-priate temperature.  
All addition of Exonuclease T must occur while the sample is inside thethermocycler while being kept at the correct temperature.

1.  Add 6μL of dilute ‘BS_Comp_5"to tube 1. 
2.  Add 6μL of dilute ‘BS_Comp_6"to tube 2. 
3.  Add 6μL of dilute 'BS_Start_Mod1_Comp5' to tube 3. 
4.  Add 6μL of dilute 'BS_Start_Mod1_Comp6' to tube 4. 
5.  Add 1μL TdT buffer and 1.4μL of water to each of the 4 tubes and mix thoroughly.
6.  Set one thermocycler, Thermocycler 1, to hold at 94◦C for two minutes, then lower the temperatureto 0◦C forever.  Place all sample tubes into Thermocycler 1 and start the protocol.
7.  Set another thermocycler, Thermocycler 2, to hold at 94◦C forever and start the protocol.8.  Keep the tubes in the thermocycler for the remainder of the experiment.

## Exoncuclease T Cleavage

1.  While the validation test samples are held in the thermocycler at the appropriate temperature, add1.6μL of Exonuclease T to each sample.
2.  After one hour of Exonuclease T incubation, rapidly transfer the four tubes to thermocycler 2.  Allowto heat inactivate for at least ten minutes.  Avoid touching the inside of the thermocycler.

## Gel Running

1.  Remove two 20% polyacrylamide gels from pouches and rinse with deionized water.
2.  Peel off tape on bottom of 20% polyacrylamide gels and remove combs.
3.  Lower  the  Buffer  Core  (the  piece  that  holds  the  gels)  into  the  Lower  Buffer  Chamber  so  that  thenegative electrode fits into the opening in the gold plate.
4.  Insert the Gel Tension Wedge into the XCell Surelock behind the buffer core.  Make sure it is in its‘unlocked’ position, which allows the wedge to slip into the unit.
5.  Insert gel cassettes into the lower buffer chamber.  The shorter “well” side of the cassette faces intothe buffer core.  The slot on the back must face outward.  If only one gel is being run, insert a bufferdam in the place of a gel cassette.
6.  Pull forward on the Gel Tension Lever toward the buffer core until the gel cassettes are snug againstthe buffer core.  This puts it in the ’locked’ position.
7.  Fill the Upper Buffer Chamber (between the gels) with running buffer.  Ensure it is not leaking.
8.  Fill the Lower Buffer Chamber completely with running buffer by pouring TBE next to the Gel TensionWedge.
9.  Pipette 12μL of running buffer into each gel well.
10.  Place the gel cover on the apparatus in the correct orientation.  Connect the electrodes to the powersource, and pre-run the gel for 30 min at 150 V. 

1.  Obtain  a  sizable  piece  of  parafilm.   Pipette  5μL  of  2x  Gel  Loading  Buffer  II  in  two  5  x  3  grids  ofdroplets, and label each droplet for the corresponding sample.
2.  For  the  ladder  well,  load  4μL  of  .5X  TBE  Buffer  into  the  already  present  5μL  Loading  Buffer  II droplets.  Load 1μL of 10/60 Ladder into the combined 9μL droplet, and mix well by pipetting upand down.
3.  For the remaining gel wells, load 5μL of the appropriate extension or test sample into the 5μL dropletof Gel Loading Buffer II already on the parafilm, mix well, and then load 5μL of the mixture directlyinto the appropriate gel well.  This should result in 20 ng/lane on a gel
4.  Run the gels at 100 V until the dark blue dye is three quarters of the way to the bottom of the gel.  If the dark blue dye is not visible, run the gel for four hours. 
5. While the gel runs, prepare 1X SYBR Gold Staining Solution with TBE as dilute.
6.  Once gel has finished running, submerge gel in SYBR Gold solution for 20 minutes.
