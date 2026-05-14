# LVMStellar

Exploratory pipeline for constructing an empirical stellar library from SDSS-V LVM observations.

## Overview

This project extracts cleaned stellar spectra from Local Volume Mapper (LVM) data using Gaia-based bright-star selection, local background subtraction and stellar-parameter comparison between LVM-DAP and Gaia DR3 GSP-Spec.

The main goal is to develop **LVMStellar**, an empirical stellar library directly matched to the LVM instrumental setup and compatible with the Representative Stellar Population (RSP) framework implemented in the LVM Data Analysis Pipeline (LVM-DAP).

## Pipeline

- reading `*.output.fits.gz` and `*.dap.fits.gz` products
- automatic identification of relevant spectral planes
- Gaia DR3 source selection
- positional crossmatching
- local background estimation and subtraction
- parametric and non-parametric gas-cleaning branches
- Gaia vs. LVM stellar-parameter comparison
- generation of diagnostic plots and cleaned spectral products

## Status

The project is currently under active development.
