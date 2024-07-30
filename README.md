## Machine_learning_AML_project

# A New Version of this Project using PyTorch is in Active Development

This brief project analyzes flow cytometry data derived from the DREAM6 Flowcap2 Acute Myeloid Leukemia challenge. Flowcap2 was a project to characterize a range of flow cytometry data, where proteins in cells are labeled with differently colored fluorophores, and the brightness of each fluorophore is measured as each cell flow past a sensor. The brightness gives a measure of the concentration of the protein in each cell.

The dataset consistes of flow cytometry data for normal and acute myeloid leukemia (AML) cells. It included fluorophore-independent data on the forward and side scattering of light by the cell (which provides information about the cell shape), as well as fluorescence measurements of for 29 specific proteins, and some non-specific fluorophores that were not supposed to bind to any proteins in the cells.  For each sample, the original dataset included measurements of these levels for a few thousand or tens of thousands of cells. The background is described here (https://www.synapse.org/#!Synapse:syn2887788/wiki/72179) with some additional information on experiments here (https://www.synapse.org/#!Synapse:syn2887788/wiki/72183). The CSV file containing the data anlyzed is included in this repository.


This project applies supervised and unsupervised machine learning tools to this dataset to predict whether a sample came from a patient with AML based on the flow cytometry results. This project was primarily run in Orange3, which is a visual programming environment where machine learning workflows can be designed and run. **A new version of this project using PyTorch is in active development, so this repository will be updated soon!**
