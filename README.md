# Cardinale-Rose-2022-GRL

This repository will host code for reproducing the results in "The Increasing Efficiency of the Poleward Energy Transport into the Arctic in a Warming Climate," Cardinale and Rose (2022). This paper is has been submitted to Geophysical Research Letters (GRL) and is currently under review (a <a href="https://www.essoar.org/doi/10.1002/essoar.10512237.1">preprint</a> is available).

`CESM_LE_data_download.ipynb` includes:
<ul> 
  <li> Code to download data from the CESM large ensemble (CESM-LE) </li>
  <li> Code to calculate the Arctic-averaged energy flux convergence </li>
  <li> Example figures and a brief overview of the Arctic surface heating efficiency metric, $E_{\textrm{trop}}$ </li>
  <li> Code to calculate $E_{\textrm{trop}}$ </li>
</ul>

`comp` includes:
<ul>
  <li> <code>functions.py</code>: user-defined functions (e.g., MSE transport and daily anomalies)</li>
  <li> <code>geocat_interp.py</code>: adapted <a href="https://github.com/NCAR/geocat-comp/blob/main/src/geocat/comp/interpolation.py">interpolation code</a> from <a href="https://geocat-comp.readthedocs.io/en/latest/">GeoCAT-comp</a> </li>
</ul>
