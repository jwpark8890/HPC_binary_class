# HPC exceedance binary classification

Backgrounds
1) To overcome the time delay of Heterotrophic Plate count (HPC)
2) HPC only show us historical data in terms of microbially safe water  
3) Culture-independent methods are fast and reliable 
4) However, culture-independent methods are not valid for water quality standards

Model description
1) Feedforward neural network
2) Culture-independent data is used for the input variable
3) Supervised for binary classification of HPC exceedance (0, pass / 1, failure)
4) Training/validation data ratio = 7:3
5) Trained using consumer tap water samples, not valid for outlet water from treatment plants
