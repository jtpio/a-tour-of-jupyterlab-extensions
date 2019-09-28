# A Tour of JupyterLab Extensions

## PyConDE & PyData Berlin 2019

### 2019-10-10

This presentation is an extended (and updated!) version of the lightning talk given at the PyData Berlin Meetup (December 2018).

JupyterLab extensions greatly improve the user experience when it comes to working with Jupyter Notebook and Data Science workflows. The extension mechanism lets third-party developers write their own extensions and contribute back to the Jupyter ecosystem.

There is now a growing number of these extensions which provide IDE-like features such as: git integration, code formatting, table of content, diagram editor, and many more.

The goal of this presentation is to complement the online documentation by doing a demo of a curated list of these JupyterLab extensions. All happening in JupyterLab.

### Layout

- Introduction to JupyterLab extensions: what are they and why are they useful? [5 min]
- Demo of 20 JupyterLab extensions in 20 minutes [20 min]
- What's next and questions? [5 min]

## Local Setup

```bash
# create an environment
conda env create

# install the extensions
chmod +x ./postBuild
./postBuild

# start JupyterLab
jupyter lab
```