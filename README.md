# TumorExpression
Tumor Type Classification from Gene Expression

Encoded ~20k-dimensional data to 100-d latent space using a Variational Autoencoder

Stripped encoder from VAE to feed into a two-layer feedforward network

Achieved 93.62% accuracy across 33 tumor types and separated into clusters using t-SNE

----------------------------------------------------------------------------------

Sample high dimensional input data:

![desc](https://github.com/JeffreyYeung7/TumorExpression/blob/master/DemoPics/SampleGene.PNG)

t-SNE Representation of the 33 tumor type expressions:

![desc](https://github.com/JeffreyYeung7/TumorExpression/blob/master/DemoPics/tSNE.PNG)

Final accuracy after training:

![desc](https://github.com/JeffreyYeung7/TumorExpression/blob/master/DemoPics/accuracy.PNG)
