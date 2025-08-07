# NSDF-OpenViSUS Cookbook

<img src="./thumbnails/nsdf.png" alt="NSDF Logo" width="300"/>

[![nightly-build](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml/badge.svg)](https://github.com/ProjectPythia/cookbook-template/actions/workflows/nightly-build.yaml)
[![Binder](https://binder.projectpythia.org/badge_logo.svg)](https://binder.projectpythia.org/v2/gh/ProjectPythia/cookbook-template/main?labpath=notebooks)
[![DOI](https://zenodo.org/badge/475509405.svg)](https://zenodo.org/badge/latestdoi/475509405)

_See the [Cookbook Contributor's Guide](https://projectpythia.org/cookbook-guide) for step-by-step instructions on how to create your new Cookbook and get it hosted on the [Pythia Cookbook Gallery](https://cookbooks.projectpythia.org)!_

This Project Pythia Cookbook covers **working with large-scale scientific data using OpenViSUS**.

## Motivation

OpenViSUS enables interactive analysis and visualization of petabyte-scale scientific datasets on any device, from supercomputers to personal laptops. This cookbook will help you learn how to store, query, and visualize big data efficiently using OpenViSUS tools and formats.

## Authors

[Aashish Panta](https://github.com/aashishpanta0), Valerio Pascucci,  Amy Gooch, [Giorgio Scorzelli](https://github.com/scrgiorgio)

### Contributors

<a href="https://github.com/sci-visus/OpenVisus/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=sci-visus/OpenVisus" />
</a>

## Structure

This cookbook is organized into sections, which you can select from the sidebar on the left (see image above). Each section covers a different topic or dataset relevant to NSDF-OpenVISUS:


### Preamble
General information and context for the NSDF-OpenVISUS Cookbook.

### Introduction to NSDF-OpenVISUS
Overview of the NSDF-OpenVISUS framework, its motivation, and its role in scientific data visualization.

### NASA DYAMOND Datasets (C1440–LLC2160)
Workflows for visualizing and analyzing NASA DYAMOND atmospheric and ocean datasets.

### ECCO LLC4320 Datasets
Visualization and analysis of the ECCO LLC4320 ocean dataset, including data access, processing, and interactive exploration.


## Running the Notebooks

You can either run the notebook using [Binder](https://binder.projectpythia.org/) or on your local machine.

### Running on Binder

The simplest way to interact with a Jupyter Notebook is through [Binder](https://binder.projectpythia.org/), which enables the execution of a [Jupyter Book](https://jupyterbook.org) in the cloud. To launch a Pythia Cookbooks chapter via Binder, click the rocket ship icon at the top right corner of the book chapter and select “launch Binder.” After a moment, you should be presented with a notebook that you can interact with. You’ll be able to execute and even change the example programs. Code cells have no output at first, until you execute them by pressing {kbd}`Shift`+{kbd}`Enter`. See [Getting Started with Jupyter](https://foundations.projectpythia.org/foundations/getting-started-jupyter) for more details.

Note: Not all Cookbook chapters are executable. If you do not see the rocket ship icon, you are not viewing an executable book chapter.

### Running on Your Own Machine

If you are interested in running this material locally on your computer, follow this workflow:

1. Clone the `https://github.com/sci-visus/OpenVisus` repository:

   ```bash
   git clone https://github.com/sci-visus/OpenVisus.git
   ```

2. Move into the `OpenVisus` directory:
   ```bash
   cd OpenVisus
   ```
3. Create and activate your conda environment from the `environment.yml` file:
   ```bash
   conda env create -f environment.yml
   conda activate openvisus
   ```
4. Move into the `Samples/jupyter` directory and start up JupyterLab:
   ```bash
   cd Samples/jupyter/
   jupyter lab
   ```

## References
- <a href="https://nationalsciencedatafabric.org/" target="_blank">National Science Data Fabric</a>
- <a href="https://github.com/sci-visus/OpenVisus" target="_blank">OpenVisus</a>
- <a href="https://github.com/sci-visus/OpenVisuspy" target="_blank">OpenVisuspy</a>

---
Please consult these papers for technical details and use cases:

- <a href="https://arxiv.org/abs/2408.11831v1" target="_blank"> Web-based Visualization and Analytics of Petascale data: Equity as a Tide that Lifts All Boats </a>
- <a href="https://arxiv.org/abs/2009.03254" target="_blank"> Interactive Visualization of Terascale Data in the Browser: Fact or Fiction?  </a>
- <a href="https://sci.utah.edu/publications/Kum2014a/KumarISC2014.pdf" target="_blank">Fast Multiresolution Reads of Massive Simulation Datasets</a>

 *Please reach out to Aashish Panta, Giorgio Scorzelli or Valerio Pascucci for any concerns about the notebook. Thank you!*
- Aashish Panta (aashishpanta0@gmail.com)
- Giorgio Scorzelli (scrgiorgio@gmail.com)
- Valerio Pascucci (pascucci.valerio@gmail.com)
