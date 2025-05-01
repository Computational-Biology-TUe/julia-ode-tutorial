# Simulation, Analysis and Parameter Estimation of Biological ODE models in Julia
Welcome! This is the repository for the **Julia Tutorial for ODE Modelling** for the **Computational Biology** group at the Department of Biomedical Engineering of Eindhoven University of Technology. Read below how to get started!

## Getting started
This getting started guide will help you to set up your Julia environment and run the examples in this repository. We will assume that you have little experience with Julia and may not even have installed it yet. If you are already familiar with Julia, and you have a working Julia installation, you can skip to the **Environment setup** section.

### Installing Julia
If you have not installed Julia, we will now guide you through the installation and the initial set-up. We will give some useful tips and tricks to set up a Julia installation that you'll be able to use comfortably after this tutorial.

### Environment setup
> [!NOTE]
> This may not work for everyone, but it is a good first try. If you have any issues, let us know!

1. **Install juliaup**: `juliaup` is the Julia version manager. It allows you to install multiple versions of Julia and switch between them easily.

2. **Install Julia**: You can install Julia using `juliaup` by running the following command in your terminal:
   ```bash
   juliaup add release
   ```

3. **Install VSCode**: If you don't have it yet, we recommend using Visual Studio Code (VSCode) as your IDE. You can download it from [here](https://code.visualstudio.com/).

4. **Install the Julia extension for VSCode**: Open VSCode and go to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window. Search for "Julia" and install the extension by Julia Computing.

5. **Install IJulia**: For optimal Jupyter notebook support, open a terminal in VSCode and run the following commands.

```
julia
```

Press `]` to enter the package manager, and then run:
```
pkg> add IJulia
```

6. **Install the project environment**: In VSCode, click open folder and select the folder where you cloned this repository. Open a terminal in VSCode and run the following commands:

```
julia
```

Press `]` to enter the package manager, and then run:
```
pkg> activate .
pkg> instantiate
```
This will install all the required packages for this tutorial.

## Organization of the tutorial
The tutorial is organized in a series of Jupyter notebooks. Each notebook contains a specific topic related to ODE modelling, simulation, and parameter estimation. The notebooks are organized in the following way:

- `1-julia-basics.ipynb`: Introduction to Julia and basic syntax.
- `2-ode-simulation.ipynb`: Introduction to ODE simulation and visualization.

Other notebooks will be added.