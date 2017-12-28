What we have: 
- Phylogeny
- Species Trait File
- Crossing file
- Geography

To do:
1. Clean / enter data
- *BI:* Clean names and traits etc such that there are no spelling errors, extra spaces etc… 
- BI: Synonymize names in all files [to make new final files for analyses]
- BI: Add additional style length data
- BI: Deal with problems arising with upon attempts to synonymize.
-- This will include new naming conventions for breeding system and ploidy variants. When doing this keep good documentation of these conventions. Have a quick qualitative summary that can be easily used in analysis [eg 1 = canonical species trait, 2 = rare type of breeding system or ploidy, 3= synthetic]
- BI:Everything in the crossing file needs a matching species trait file.
- YB: Look under the hood of geography data to get a sense of how to reanalyze, and if/how to deal with this downstream. 
- BI: Upload to git

2. Analysis files
- YB: Make sure cophenetic phylo is working. 
- YB: Yaniv clean up analysis pipeline, comment it etc… make sure it plays nice with arbitrary file names, including the new ones. 
- YB: Comment code with transparent naming convention
- YB & BI: Stats. Can we tell what matters more, ploidy, breeding system, or style length match

3. Figures
- YB: Cross success over time. Some visualization trick to avoid over plotting and guide the eye.
-- Makes for (1) No phylo correction. (2) Node weighted averages (3) Only sisters
- YB: Effect of mating system on cross success
- YB: Effect of ploidy on cross success
- YB: Style length matching
- YB: Geographic range overlap
- YB: Revisit phylo correlation and other excess figures
- BI: Clean up figures


4. Writing
