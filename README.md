![Model Syncronization](Corr_Panel_Prog.png "Network + Performance")

# Repository to Create All Figures in:
## **_A Framework for Atmosphere Connected SuperModels_**

**Authors:**
- **Will Chapman** (NSF - NCAR) [wchapman@ucar.edu](mailto:wchapman@ucar.edu)
- **Francine Schevenhoven** (NSF - NCAR) [Francine.Schevenhoven@uib.no ](mailto:Francine.Schevenhoven@uib.no )
- **Judith Berner** (NSF - NCAR) [berner@ucar.edu](mailto:berner@ucar.edu)
- **Noel Keenlyside** (UiB - GFI)
- **Ingo Bethkee** (UiB - GFI) 
- **Ping-Gin Chiu** (UiB - GFI)
- **Alok Kumar Gupta** (UiB - GFI) 
- **Jesse Nusbaumer** (NSF - NCAR)


William E. Chapman 1, Francine Schevenhoven 2, Judith Berner 1, Noel Keenlyside 2, Ingo Bethke 2,
Ping-Gin Chiu 2, Alok Kumar Gupta 2, and Jesse Nusbaumer 

### File Directory Path:
To create any figure in the study please run the following notebooks: 

**Figure 02:**
- `.-|-> ./Wind_Hist.ipynb`

**Figure 03:**
- `.-|-> ./Wind_Hist.ipynb`
- 
**Figure 04:**
- `.-|-> ./Wind_Hist.ipynb`

**Figure 05:**
- `.-|-> ./Wind_Hist.ipynb`

- **Figure 06:**
`.-|-> .MOV/*.ipynb`

### Supplemental Figures:

**Wheeler-Kiladis:**
- `.-|-> ./CMJO_Diagnostic_Tool/wk_spectra/*`

**Bias Panel Plots:**
- `.-|-> ./Climo_Bias_Tiles/CLIMO_Tiles.ipynb`

**OMEGA Bias:**
- `.-|-> ./Omega/OMEGA_WALKER.ipynb`

### Abstract

In this study, we develop a novel approach to correct biases in the atmospheric component of the Community Earth System Model (CESM) using convolutional neural networks (CNNs) to create a corrective model parameterization for online reduction. By learning to predict systematic nudging increments derived from a linear relaxation towards the ERA5 reanalysis, our method dynamically adjusts the model state, significantly outperforming traditional corrections based on climatological increments alone. Our results demonstrate substantial improvements in the root mean square error (RMSE) across all state variables, with precipitation biases over land reduced by 25-35%, depending on the season. Beyond reducing climate biases, our approach enhances the representation of major modes of variability, including the North Atlantic Oscillation (NAO) and other key aspects of boreal winter variability. A particularly notable improvement is observed in the Madden-Julian Oscillation (MJO), where the 
