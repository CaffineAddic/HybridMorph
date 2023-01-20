# HybridMorph
Just a experiment with voxelmorph and synthmorph combination 


It the models in a folder named aptly 
If you want to load weights from the trained model please use the correct path in the code
HybridMorph_FewShots_WeightsLoad & HybridMorph_alphaVar_LoadWeights are the main two model gerating algoritms which vary by using different paramenter value of alpha and the number of real brain images used.


AlphaVarCSV_visual and FewShotCSV_visualizationLoss are just to comapre losses and see the difference with parameter traning.


the models FewShot_XXX and FewShot_XXX are trained with the same parameters on the same data but they differ in batch size (8 vs 32)

credits

To the voxelmorph team for the source code link:https://github.com/voxelmorph/voxelmorph
