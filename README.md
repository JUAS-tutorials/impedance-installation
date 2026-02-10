# Installation instructions for the impedance and collective effects tutorial

This tutorial assumes that you have followed the xsuite installation tutorial from https://github.com/JUAS-tutorials/xsuite-installation

On Windows, start an Ubuntu terminal (with Windows Subsystem for Linux).
On Linux or macOS, start a new terminal.

## Dowload the requirements file

- Do `wget https://github.com/JUAS-tutorials/impedance-installation/raw/refs/heads/main/requirements.txt` in the terminal
- Or download from this link: https://github.com/JUAS-tutorials/impedance-installation/raw/refs/heads/main/requirements.txt
- Browse to where the file was downloaded
    - Usually `cd ~/Downloads`

## Create the environment

- `conda create --name juas-impedance python==3.11` create a new python 3.11 environment
- `conda activate juas-impedance` activate this new environment
  
FOR WINDOWS USERS ONLY: `conda install -c conda-forge compilers gcc`

- `pip install -r requirements.txt` install all the packages needed with a specific version

## Start jupyter lab

- `jupyter lab` in the terminal, and open the link prompted in the shell
