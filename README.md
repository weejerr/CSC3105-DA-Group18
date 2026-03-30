# CSC3105 Data Analytics — Group 18
> Singapore Institute of Technology (SIT) | University of Glasgow (UofG) | CSC3105 Data Analytics

## Overview
This repository contains the dataset and analysis notebook for Group 18's CSC3105 Data Analytics project. The project applies machine learning to **Ultra-Wideband (UWB) signal classification and ranging error correction**, using a two-stage pipeline to improve indoor positioning accuracy.

## Group Members
| Name | Student ID | Glasgow ID |
|---|---|---|
| Chen Jieyang | 2400648 | 3070593C |
| Kwok Chang Feng Zenden | 2402538 | 3070693K |
| Lim Wei Zhe Bryan | 2401331 | 3070646L |
| Tan Bao Quan | 2402547 | 3070694T |
| Tang Wee Jer | 2403409 | 3070571T |

## Project Goal
UWB signals are affected by **Line-of-Sight (LOS)** and **Non-Line-of-Sight (NLOS)** conditions, where obstacles and reflections introduce ranging errors of up to 3–5m. This project builds a pipeline to:

1. **Classify** each signal path as LOS or NLOS
2. **Correct** the ranging error for LOS signals using a regression model
3. **Extract** a secondary CIR path for additional range estimation

## How to Run
1. Clone or download this repository
2. Open `DA_Group18.ipynb` in Jupyter Notebook or JupyterLab
3. Run all cells from top to bottom (**Kernel → Restart & Run All**)
