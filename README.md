# Rin G

Full-stack software engineer with research background, specializing in data visualization and design. 

*(Note: Unfortunately the bulk of my work has been NDA and I'm still in the processing of making visualizations hostable without revealing protected data. However today I'm putting up a small sample of past work.)*

## Web-based Visualization examples for scientific data

### Project: Aggregated Bioreactor Data Visualization in the Cloud  

A large project coded in React/redux. Uses an extensive API pulling from complex datasources. High interactability (via user context) by Plotly and React. 

[!['cloudviz'](timecloudviz_overview.png)](https://raw.githubusercontent.com/seve-rin-g/seve-rin-g.github.io/refs/heads/main/timecloudviz_overview.png)

This screenshot shows 6 time-series plots (pH, DO2, Temperature, Base Flow, CO_2, pH Calibration offsets -- these are diverse data-types) for 12 small-scale bioreactors. The application is performant up to ~48 bioreactors. 

If the experiment is active, the plots will update in real-time. 

Users typically use this to monitor experiments live, while overlaying them with past experiment performance, and can export data for local statisical analysis if needed.


### Project: Variability in Raw Material Vendor lots

A small (1-page) project coded in d3/js, showing bar/scatter plots. Small, researcher-maintained datasource.

#### Plot functionality overview

!['RMV plot demonstration'](https://github.com/seve-rin-g/material-component-analysis/raw/main/rmv_graphs.gif)

Left scatter plot: the contribution of each component (x-axis) to the final measured trace element concentration (y-axis). Hovering shows the vendor lot and assay number so users can follow up as needed.

Right stacked bar plot: this gives the user an idea of the min, max, and average ranges of this trace element (in this case, Mn) that they might see in this process.

#### The user can scroll through many plots

!['RMV scroll'](https://github.com/seve-rin-g/material-component-analysis/raw/main/rmv-scroll.gif)

The embedded table is populated with data from a GCP asset maintained by Media Development researchers, but can be edited within the browser. The page generates 16x2 plots total (colors conserved across the plots).

## Non-scientific visualization design work

Generative visualization of 3 FFT bins in JS/P5, contract for a composer client. (This is a dev session; the final product was a "live-coding" performance in front of an audience.)

<video controls src='https://github.com/user-attachments/assets/1757d33e-37a8-4078-ad76-4be0889dbc15
' width="100%"></video>



