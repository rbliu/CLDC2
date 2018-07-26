# Plotting Shear Distribution of Background Galaxies in DC2 Run 1.1p extra-galactic catalog (protoDC2)

In this example script we show how to select background galaxies distorted by the foreground host halo, and calculate their shear distributions.

Participants: **Ian Dell'Antonio**, **Robert Liu**, **Shenming Fu**

Last verified run: **7-26-18**

This notebook demonstrates how to access the extra galactic catalog through the Generic Catalog Reader (GCR, https://github.com/yymao/generic-catalog-reader) as well as how filter on galaxy features and cluster membership.

__Objectives__:

1. Access extra galactic catalog (ProtoDC2) through the GCR.
2. Select galaxy cluster centrals as a proxy for clusters.
3. Select background galaxies filtered by position and redshift.
4. Plotting tangential shear of the background galaxies vs. their distances to the host halo center.


__Logistics__: This notebook is intended to be run through the JupyterHub NERSC interface available here: https://jupyter-dev.nersc.gov. To setup your NERSC environment, please follow the instructions available here: https://confluence.slac.stanford.edu/display/LSSTDESC/Using+Jupyter-dev+at+NERSC
