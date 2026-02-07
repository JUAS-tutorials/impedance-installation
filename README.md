# Installation instructions for the impedance and collective effects tutorial

This tutorial assumes that you have followed the xsuite installation tutorial from https://github.com/JUAS-tutorials/xsuite-installation

On Windows, start an Ubuntu terminal (with Windows Subsystem for Linux).
On Linux or macOS, start a new terminal.

## Dowload the requirements file

- `curl `
- Or dowload from this link:
- Browse to where the file was downloaded
    - Usually `cd ~/Downloads`

## Create the environment

- `conda create --name juas-impedance python==3.10` create a new python 3.10 environment
- `conda activate juas-impedance` activate this new environment
- `pip install -r requirements.txt` install all the packages needed with a specific version

## Start jupyter lab

- `jupyter lab` in the terminal, and open the link prompted in the shell
