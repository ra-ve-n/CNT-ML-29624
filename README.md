***********************************************************************************************************************
Please cite the following paper if you use the data stored in this repository:

@article{malek2024predicting,
  title={Predicting the mechanical properties of pristine and defective carbon nanotubes using a random forest model},
  author={Malek, Ihtesham Ibn and Sarkar, Koushik and Zubair, Ahmed},
  journal={Nanoscale Advances},
  year={2024},
  publisher={Royal Society of Chemistry}
}

DOI: 10.1039/D4NA00405A
**********************************************************************************************************************

~dataset_combined: Dataset comprising parameters of pristine and defective CNT with single vacancy employed in training 
machine learning model.

column 1: binary indicator (0/1: pristine/defective).
column 2-3: chiral indices (n,m).
column 4: tensile strength.
column 5: fracture strain.
column 6-7: 2nd/1st order coefficient of symmetric second Piola-Kirchoff stress equation.
column 8-12: 4th-0th order coefficient of polynimial equation for Poisson's ratio-strain variation curves.
column 13-14: RMSE calculated from fitted and calculated curves of stress/Poisson's ratio variation with strain.

~CNT_SS_RF_ndc.docx: python code.

~Best_multioutput_regressor_ndc.pkl: best model.
