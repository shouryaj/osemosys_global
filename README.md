![Geographic scope](./docs/_static/osemosys-global.png "Geographic scope")

# Future Energy Outlook

## Overview
'Future Energy Outlook' (FEO) is an open source electricity system model generator
with global coverage. It uses [OSeMOSYS Global](https://www.nature.com/articles/s41597-022-01737-0) as 
a starting point and can be used to create inter-connected energy
systems models for both the entire globe and for any geographically diverse
subset of the globe. It is built using the fully open-source 
[OSeMOSYS](https://osemosys.readthedocs.io/en/latest/) energy system modelling tool.!

## Getting started

### Setup on MacOS

#### 1. Install `GLPK`

[GNU GLPK](https://www.gnu.org/software/glpk/#downloading) package is a open-source linear programming package. OSeMOSYS Global uses it to create a linear programming file.

We can install `GLPK` using `homebrew`. If you haven't installed `homebrew` yet, you can download the `.pkg` file [here](https://github.com/Homebrew/brew/releases/tag/4.1.12) or run the following command in your terminal:

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Run the following command to install `GLPK`:

```bash
brew install glpk
```

Once installed run the command `glpsol` in the command line. The following message will display indicating that GLPK has installed correctly.

```
$ glpsol

GLPSOL: GLPK LP/MIP Solver, v4.65
No input problem file specified; try glpsol --help
```

#### 2. Install a Solver

## Useful Links

- [FEO Documentation](https://feo-esmod-osemosys.readthedocs.io/en/latest/)
- [OSeMOSYS Global Documentation](https://osemosys-global.readthedocs.io/en/latest/installation.html)
