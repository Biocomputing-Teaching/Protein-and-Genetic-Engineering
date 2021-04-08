# Protein and Genetic Engineering

## Welcome to the course!

This page is the official repository for the course "Protein and Genetic Engineering" of the Bachelor's Degree in Bioengineering at the UIC.

The repository contains the material created or adapted from other (referred) sources to introduce the field of computational protein modeling and design.

The course will employ Python as a standard programming language.

## Getting started

Protein engineering is the rational modification of protein molecules to achieve a desired functional change in the macromolecule's behavior. There are several reasons you would like to modify a protein to develop useful or valuable results (we will discuss this during our theoretical sessions).

Most protein engineering comes in two forms: rational design or directed evolution methods. We will mainly focus on the first method, specifically in rational computational design. Therefore, all practical sessions will be carried out using computational tools. For this reason, we must have the proper tools to get the work done.

### Preparing the tools

Before we start with the course's practical session, you should have everything set up and ready to work. Our primary language will be Python, a general programming language every day more ubiquitous. Many platforms can host a Python interpreter, but since this is not the only application we will use during the course, we will need a shared operating system among all the course attendants. For this, we choose Linux since most scientific applications are developed for it.

Linux and macOS are very alike since both have similar architectures. Many Linux programs are also available for macOS users. So, you can use the terminal application in your MacOS to follow the course for most purposes.

There are several ways to install Linux. One way is using it as your primary operating system (OS) and do everything you usually do but now using Linux (We, bioinformaticians usually prefer this option).

We recommend you to get Ubuntu to start using Linux:

[Get Ubuntu](https://ubuntu.com/)

Besides, there are ways of having more than one OS in your personal computer that you can select at startup (when you turn on your computer). If you have a Windows computer and you want to keep your current OS, this is your option:

[How to set up a computer with dual-booting](https://itsfoss.com/install-ubuntu-1404-dual-boot-mode-windows-8-81-uefi/)

Finally, if you don't want a second OS on your computer, you can set up a Linux virtual box from Windows:

[How to set up a Linux virtual machine for Windows with VirtualBox](https://itsfoss.com/install-linux-in-virtualbox/)

This last option is not highly recommended since you'll need a powerful computer to run two OSs efficiently.

Before proceeding, we strongly recommend you to backup all your personal data before attempting any OS modification to your computers.

### Installing the required programs

* Conda (Miniconda)
First, we will need to install the [Miniconda](https://docs.conda.io/en/latest/) package manager:

[Documentation for installing Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)

After installing Conda, we will install several packages needed for our sessions. Open up a terminal on your [Linux](https://www.lifewire.com/ways-to-open-a-terminal-console-window-using-ubuntu-4075024) or [Mac](https://www.howtogeek.com/682770/how-to-open-the-terminal-on-a-mac/) and execute the following:

* Install [jupyter notebooks](https://jupyter.org/install):
```
conda install jupyterlab
```

* Install Pymol:
```
conda install -c samoturk pymol
```

* Install [Git](https://git-scm.com/)
```
conda install -c anaconda git
```

* Install PyRosetta from Conda:

To install PyRosetta from Conda, you will need to get an Academic License for PyRosetta; use the following link to ask for an academic license:

[PyRosetta Software Academic License](https://els2.comotion.uw.edu/product/pyrosetta)

Once you have your license, you need to use the username and password provided and execute the following command:

```
conda config --add channels https://USERNAME:PASSWORD@conda.graylab.jhu.edu
```

Please, be sure you replace the uppercase words USERNAME and PASSWORD in the above command for the ones you got from the PyRosetta licensing. After that install PyRosetta with Conda:

```
conda install pyrosetta
```

* Other required Python packages:
```
conda install numpy
conda install matplotlib
conda install biopython
```

## Sessions

The course's module will be divided into theoretical and practical sessions. Here, you will find the necessary information for each one of those sessions. Please read the information within each appropriate link before you come to a particular session.
