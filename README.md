## Machine learning model for CCA(Complex Concentrated Alloys) using TensorFlow

Author: Soumen Basak

This is a work-in-progress of a machine learning model to attempt to predict the Vickers hardness of CCAs.

The image below shows the comparison between the values indicated in the articles and the values predicted by the model. 
The data was divided between training set and test set. 

![Train and test results](https://github.com/NoobMaster1999/Prediction-the-Vickers-hardness-of-CCA/blob/main/Images/Test%20train%20prediction%20experimental%20HV.png)

This model considers the composition of the alloy, some descriptive parameters (such as VEC, atomic size difference and mixing enthalpy) and its condition. There are five conditions currently used:
 - AC: As-cast
 - HM: Homogenized
 - WR: Work hardening
 - PM: Powder metallurgy
 - AM: Additive manufacturing
 
 
References of the database

[1] GORSSE, Stéphane et al. Database on the mechanical properties of high entropy alloys and complex concentrated alloys. Data in brief, v. 21, p. 2664-2678, 2018. https://doi.org/10.1016/j.dib.2018.11.111

[2] WEN, Cheng et al. Machine learning assisted design of high entropy alloys with desired property. Acta Materialia, v. 170, p. 109-117, 2019. https://doi.org/10.1016/j.actamat.2019.03.010

[3] JAIN, Harsh et al. Phase evolution and mechanical properties of non-equiatomic Fe–Mn–Ni–Cr–Al–Si–C high entropy steel. Journal of Alloys and Compounds, p. 155013, 2020. https://doi.org/10.1016/j.jallcom.2020.155013

[4] TORRALBA, J. M.; ALVAREDO, P.; GARCÍA-JUNCEDA, Andrea. High-entropy alloys fabricated via powder metallurgy. A critical review. Powder Metallurgy, v. 62, n. 2, p. 84-114, 2019. https://doi.org/10.1080/00325899.2019.1584454

[5] SONI, Vinay Kumar; SANYAL, Shubhashis; SINHA, Sudip K. Phase evolution and mechanical properties of novel FeCoNiCuMox high entropy alloys. Vacuum, v. 174, p. 109173, 2020. https://doi.org/10.1016/j.vacuum.2020.109173

[6] BORG, Christopher KH et al. Expanded dataset of mechanical properties and observed phases of multi-principal element alloys. Scientific Data, v. 7, n. 1, p. 1-6, 2020. https://doi.org/10.1038/s41597-020-00768-9
