# MBP/FIB Colocalization Analysis

This repository contains a Python script for analyzing colocalization of oligodendrocytes with nanofibers. Masks were pre-generated using iLastIK. 

# Structure 

jack_bootcamp/
├── data/
│ └── masks/ # Input TIFF masks (Max_MBP_Mask_.tif and Max_Fib_Mask_.tif)
├── output/ # Script output: CSVs and plots
├── jack_bootcamp.ipynb
├── environment.yml 
└── README.md 

```bash
git clone https://github.com/your-username/mbp-fib-colocalization.git
cd jack_bootcamp

conda env create -f jack_bootcamp.yml
conda activate jack_bootcamp-env

python jack_bootcamp.py 
