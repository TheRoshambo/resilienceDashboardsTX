# Open Source Data Integration, Analysis, and Visualization Dashboard

* Open source dashboard data cleaning and integration software developed for the [Identifying Resilience Factors in Texas Public Schools](2022Fall-CHERR-Poster.pdf) project
* Dashboard Authors: [Daniel Payan](https://github.com/danielpayan13) and [Jelena Tešić](jtesic.github.io), Computer Science Department, Texas State University
* Project collaborator and data provider: [Li Feng](https://lifeng.wp.txstate.edu/), Department of Economics, Texas State University 

**Acknowledgements** The work has been supported by [CHERR](https://www.cherr.txst.edu/) and [Data Lab](DataLab12.github.io) at Texas State University. 

## SETUP
  1. Download Anaconda/Juptyer Notebook for your device's operating system from [here](https://www.anaconda.com/products/distribution#Downloads)
  2. Run Anaconda Prompt app with administrative privileges
     * make sure all the conda packages are up to date: ```conda update --all```
       * answer Yes to install all packages   
     * install needed packages as follows: 
       * the [bokeh](https://anaconda.org/bokeh/jupyter_bokeh) package: ```>>conda install -c bokeh jupyter_bokeh```
       * the [hv_plot](https://anaconda.org/conda-forge/hvplot), the [panel](https://anaconda.org/conda-forge/panel), and [geopandas](https://geopandas.org/en/stable/getting_started/install.html) packages: ```>>conda install -c conda-forge hvplot panel geopandas```
       * [openpyxl](https://anaconda.org/anaconda/openpyxl) package: ```conda install -c anaconda openpyxl```
       * [plotly express](https://anaconda.org/plotly/plotly_express) package: ```conda install -c plotly plotly_express```
  3. close the anaconda prompt and open it up as a regular user , type ```>>jupyter notebook```
     * navigate in the browser to this folder and double click on the [JointDashboard.ipynb](JointDashboardh.ipynb) or [District_CountyDashboard.ipynb](District_CountyDashboard.ipynb) to open them (separate windows will open)
     * in separate windows, click `Cell` on the top taskbar and then `Run All`. This will open the the tabbed dashboard.

## [Data](Data) - source for integrated data diplayed by fourdashboard

* [JointDashboard](JointDashboard.ipynb) -> outputs 2 tabs
    * Tab 1 displays a set of three county-level maps of Texas which reflect percent changes in Staff/Student population, STAAR testing scores, and the workforce from 2019 to 2021.
    * Tab 2 displays a histogram of the percent changes in STAAR scores along with a heatmap that models change based on demographic group and grade from 2019 to 2021.

* [District_CountyDashboard](District_CountyDashboard.ipynb) -> outputs 3 tabs
    *  Tab 1 displays a set of nine district-level maps of the highest population counties in Texas which reflect percent changes in Staff/Student population, STAAR testing scores, and the most influential features for these STAAR changes.
    *  Tab 2 displays a set of nine district-level maps of counties along the I-35 Austin area in Texas which reflect percent changes in Staff/Student population, STAAR testing scores, and the most influential features for these STAAR changes.
    *  Tab 3 displays a district-level map of Texas which reflects percent changes in Staff/Student population, STAAR testing scores, and the most influential features for these STAAR changes.
    
