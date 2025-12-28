# geology-datasets
Geological datasets
# Supplemental Data for: Evidence for Riemannian Spectral Statistics in Crustal Fracture Networks

## Dataset Overview
This repository contains the high-resolution fracture spacing dataset derived from 2,000+ drill core photographs from the Abitibi Greenstone Belt (Quebec, Canada).

## File Description: `Dataset_S1_Abitibi_Vein_Spacing.csv`
The dataset includes 1,256 validated vein spacing measurements from 4 boreholes (A-ZK-001 to 004).

### Column Definitions
- **Borehole_ID**: Unique identifier for the drill hole (e.g., A-ZK-001).
- **Photo_ID**: Original filename of the high-resolution core photograph.
- **Vein_ID**: Sequential identifier for each mineralized vein.
- **Lithology_Type**: 
  - `Au-Quartz_Vein`: Gold-bearing quartz-carbonate veins.
  - `VMS_Sulfide_Stringer`: Semi-massive sulfide veins (VMS style).
- **Spacing_Ln_cm**: Measured distance between the center of Vein(n) and Vein(n+1) in centimeters.
- **Spacing_Ratio_r**: The adjacent spacing ratio ($r = L_n / L_{n+1}$), used for calculating the ISS index.

## Methodology
Data was extracted using an automated orthorectification pipeline calibrated by physical depth markers (e.g., at 123.00 m). The mean spacing ratio for the entire dataset is $\langle r \rangle \approx 0.702$, consistent with the Intermediate Spectral State (ISS).

## License
Creative Commons Attribution 4.0 International (CC BY 4.0).
