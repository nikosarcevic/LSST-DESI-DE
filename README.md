# Quick check: LSST with evolving DE
*Upon request from Z. Ivezic.*

Here we present and compare the results for four 3x2pt forecasting scenarios for the LSST survey.
The first scenario is the LSST SRD which is the current LSST forecast (for epochs Y1 and Y10).
The second scenario is the LSST forecast for Y1 and Y10 with evolving DE parameters $w_0$ and $w_a$.
The fiducial values of the cosmological parameters (except the DE parameters) are the same for all scenarios.
The fiducial values of the DE parameters are $w_0 = -1$ and $w_a = 0$ for the LSST SRD scenario
 while for the LSST forecast with evolving DE parameters they are:
  - $w_0 = -0.727$ and $w_a = -1.05$ (DESI+CMB+DESY5).
  - $w_0 = -0.86$ and $w_a = -0.6$ (similar to DESI+CMB+Pantheon modified in light of LSST results with DESI+CMB+DESY5 and figure G2 from DESC SRD).
Note that for the $w_0 w_a$CDM scenarios, I have used errors from DESI results!

The values of th evolving DE parameters and their errors are taken from the DESI R1 results
 (see Table 3 in [DESI 2024 VI: Cosmological Constraints from the Measurements of BAO](https://arxiv.org/pdf/2404.03002) paper).



 **Feel free to use the results (with credits).**
 

 ![w0wa plot](https://github.com/nikosarcevic/LSST-DESI-DE/blob/main/plots_output/3x2pt_lsst_desi_comparison_y1y10_w0wa.png))

 ## More informative plots:
 **Comparison of the ratios of the errors on the parameters**
 
 ![sigmas ratios](https://github.com/nikosarcevic/LSST-DESI-DE/blob/main/plots_output/sigmas_ratios.png))

  **Comparison of the absolute difference of the errors on the parameters**
  
 ![sigmas diffs](https://github.com/nikosarcevic/LSST-DESI-DE/blob/main/plots_output/sigmas_diffs.png))
