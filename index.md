An analysis workflow and r script to -

Find the inter-facial atoms and render the 3d image of a surface
Quantify rms roughness from the interfacial atoms
WorkFLow :

To render 3d image of interface:: Mem. Gro ⇾ Mem.csv ⇾ Interfacial_atoms.R (Find the interfacial atoms) ⇾ Interfacial_Atoms_rawdata.csv (This is done for grid size is 2A*2A) ⇾ 3dSurface_data.xlsx (Format the data as number of gridwise you used in the R program to render the 3d interface) ⇾ Rendered Polyamide Membrane interface - 1.tif / Rendered Polyamide Membrane interface - 2.tif

To quantify rms of roughness:: Interfacial_Atoms_rawdata.csv (This is done for grid size is 2A*2A) ⇾ 3dSurface_data.xlsx (choose big grid size from here if you need) ⇾ RMS_roughness.xlsx (Calculate rms roughness for grid size 4A * 4A)
d
