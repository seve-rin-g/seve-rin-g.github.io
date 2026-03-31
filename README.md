# Rin G

Full-stack software engineer with research background, specializing in data visualization and design. 

## Note

I am just putting this portfolio together. 
Unfortunately the bulk of my work has been NDA and I'm still in the processing of extracting everything. 

However today I'm putting up a small representative sample of high-density scientific visualization.

## Visualization examples

### Project: Cloud Viz

A large project coded in React/redux. Uses an extensive API pulling from complex datasources. 

### Project: Variability in Raw Material Vendor lots

A small (1-page) project coded in d3/js, showing bar/scatter plots. Small, researcher-maintained datasource.

#### Plot functionality overview

!['RMV plot demonstration'](https://github.com/seve-rin-g/material-component-analysis/raw/main/rmv_graphs.gif)

Left scatter plot: the contribution of each component (x-axis) to the final measured trace element concentration (y-axis). Hovering shows the vendor lot and assay number so users can follow up as needed.

Right stacked bar plot: this gives the user an idea of the min, max, and average ranges of this trace element (in this case, Mn) that they might see in this process.

!['RMV scroll'](https://github.com/seve-rin-g/material-component-analysis/raw/main/rmv-scroll.gif)

The embedded table is populated with data from a GCP asset maintained by Media Development researchers, but can be edited within the browser. The page generates 16x2 plots total (colors conserved across the plots).
