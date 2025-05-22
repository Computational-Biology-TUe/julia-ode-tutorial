# Simulation, Analysis and Parameter Estimation of Biological ODE models in Julia
Welcome! This is the repository for the **Julia Tutorial for ODE Modelling** for the **Computational Biology** group at the Department of Biomedical Engineering of Eindhoven University of Technology. Read below how to get started!

> [!WARNING]
> This repository is a work in progress. I am continuously adding new content and improving the existing material. If you have any suggestions or feedback, please add an issue! I am always looking for ways to improve this repository and make it more useful for everyone. Thank you for your understanding!

## Getting started
This getting started guide will help you to set up your Julia environment and run the examples in this repository. We will assume that you have little experience with Julia and may not even have installed it yet. If you are already familiar with Julia, and you have a working Julia installation, you can skip to the **Setup**

### Installing Julia
If you have not installed Julia, we will now guide you through the installation and the initial set-up. We will give some useful tips and tricks to set up a Julia installation that you'll be able to use comfortably after this tutorial.

> [!NOTE]
> This may not work for everyone, but it is a good first try. If you have any issues, let us know!

1. **Install [juliaup](https://github.com/JuliaLang/juliaup)**: `juliaup` is the Julia version manager. It allows you to install multiple versions of Julia and switch between them easily.

2. **Install Julia**: You can install Julia using `juliaup` by running the following command in your terminal:
   ```bash
   juliaup add release
   ```

### Setup

1. **Install Pluto**: The tutorial notebooks are written in [Pluto.jl](https://plutojl.org/), a reactive notebook environment for Julia. You can install Pluto by running the following commands in your terminal:

First, start Julia:
   ```bash
   julia
   ```

Then, press `]` to enter the package manager, and run:
   ```julia
   pkg> add Pluto
   ```

2. **Run Pluto**: After installing Pluto, you can run it by executing the following command in the Julia REPL:
   ```julia
   using Pluto
   Pluto.run()
   ```
   This will open a new tab in your web browser with the Pluto interface. From there, you can open and edit the notebooks in this repository. Pluto takes care of the installation of all the required packages for you.

## Organization of the tutorial
The tutorial is organized in a series of Pluto notebooks. Each notebook contains a specific topic related to ODE modelling, simulation, and parameter estimation. The notebooks are organized in the following way:

<!-- - `1-julia-basics.ipynb`: Introduction to Julia and basic syntax. -->
- `2-ode-simulation.jl`: Introduction to ODE simulation and visualization.

Other notebooks will be added later.
