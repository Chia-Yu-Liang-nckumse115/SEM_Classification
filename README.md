#Overview

This project implements a 10-class SEM microstructure classification model.
Given a new SEM image, the model outputs the probability distribution over the following categories:

Biological

Fibres

Films / Coated Surface

MEMS Devices and Electrodes

Nanowires

Particles

Patterned Surface

Porous / Sponge

Powder

Tips

You may use np.argmax on the output probabilities to obtain the predicted class.

#Parctical Applications

1. Large-scale SEM Dataset Organization
Automatically categorize thousands of SEM images into 10 microstructure classes — eliminating the need for manual sorting by students or assistants.

2. Automated Materials Characterization
Analyze the distribution of microstructure types (e.g., Powder, Porous/Sponge, Nanowires) under different processing conditions.

3. Quality Assurance (QA) Pre-Screening
Identify abnormal patterns in SEM images of MEMS devices, such as unexpected Patterned Surface features or Powder-like defects.
