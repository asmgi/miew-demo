# Miew demo

## Loading molecules/proteins

To load multiple molecules, the Multifile support flag should be ON. When loading the first molecule, it should be turned OFF, so that the scene is cleared before loading.
![multifile](ss-multifile.png)

When ligand is loaded, all models representations are reset to "balls and sticks" (it can be fixed, ofcourse):
![two molecules](ss-twomol.png)

So the next step is to fix this, by setting the protein's representation to cartoon in the representations menu.
First, select the molecule.
![representations](ss-repr.png)

Then select **Cartoon** for **Mode** instead of **Balls**
![cartoon](ss-repr-cartoon.png)

The result is this (in this case ligand is not aligned to protein, we just used a non-processed files for visuals demonstration):
![result](ss-result.png)
