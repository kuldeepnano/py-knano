# py-knano
This repository contains python jupyter notebooks for transport measurements.

Instruments covers:-

* Stanford Research Instruments SR830
* Stanford Research Instruments SR860
* American Magnetic Inc. Model 430 (ami430)
* Lakeshore Model 370
* Lakeshore Model 372
* NI-DAQ USB-6341

Progams:-
* Sweeping magnetic field using ami430
* Logging parameters of ami430
* R vs Time measurement using SR830
* R vs B measurement using SR860
* dVdI sweeps vs B measurements using SR860
* Waform generation using NI-DAQ
* DC Voltage measurement using NI-DAQ
* Time trace of input Voltage using NI-DAQ
* FFT and PSD of input VOltage using NI-DAQ

## Creating new files. Use following files for next use.

requirements.txt file contains required python packages
knano_measure.ipynb (for general use) **ongoing**
knano_plotting.ipynb (for plotting data) **ongoing**
knano_lakeshore.ipynb (for reference of lakeshore 370/372 functions) **ready for 14T (LAN) and Fincryo (GPIB) connections; Fincryo (API) will be added soon**
knano_ami430.ipynb (for reference of AMI 430 funcitons) **old**
knano_bilt.ipynb (for reference of BILT Voltage source) **old**
knano_NIDAQ_noise.ipynb (for reference of NIDAQ for noise measurement) **ongoing**
knano_NIDAQ.ipynb (for reference of NIDAQ for general IV and AWG) **old**

knano_14T.ipynb (for use at 14T cryostat) **old**
knano_Fincryo.ipynb (for use at Fincryo) **old**
knano_Prototype.ipynb (for use at Prototype) **will be adding soon**
knano_Optonano.ipynb (for use at Opto-Nano) **will be adding soon**
knano_NANOY.ipynb (for use at NANO-Y) **will be adding soon**
knano_DeMag.ipynb (for use at DeMag) **will be adding soon**

## New Updates

* File explorer window opens for saving and loading data files. New functions for saving, appending and loading data files