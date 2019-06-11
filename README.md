# River Hydrodynamics Simulation

Hydraulic infrastructures management and operation are challenging issues. Considering climate changes, risks and uncertainties, it is increasingly important to assure environmental, economic and social sustainability. The use of adequate and efficient tools can contribute with solutions supported on hydrodynamic models, used **to simulate the flow of water along river channels and floodplains**.

On the other hand, Web-based tools can provide a suitable environment to illustrate the hydrodynamics behavior of a given river under different conditions and to evaluate various scenarios and management strategies. Moreover, this approach can also be considered as an academic resource for **learning purposes**.

This work presents a Web interface, supported by a Jupyter Notebook, which provides functionalities **to configure a hydrodynamic river model and simulate its behavior**. The model setup is run through the [MIKE 1D numerical simulation engine](http://docs.mikepoweredbydhi.com/engine_libraries/mike1d/mike1d_api/) behind [MIKE HYDRO River](https://www.mikepoweredbydhi.com/products/mike-hydro-river) commercial software.  

This approach considers the Mondego River as a case study and allows the use of different datasets for different meteorological conditions, although here, for demonstration purposes, a particular dataset is used. This tool also provides access to real data, such as water levels and streamflows, collected by geosensors located in the considered area.

## Troubleshooting

Jupyter Notebook or IPython Notebook files with a .ipynb extension on GitHub, they will render as static HTML files in the repository. The interactive features of the notebook, such as custom JavaScript plots, will not work on GitHub. So, to view the Jupyter notebook river_hydrodynamics_simulatins.ipynb in this repository you can use [nbviewer](https://nbviewer.jupyter.org/).
