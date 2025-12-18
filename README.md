# MAST397 Final Project – Substitution Timing and Team Intensity

## Installation

# The project uses Python

```bash
pip install -r requirements.txt

## Using the data from Metrica Sports

Download the required files from the Metrica Sports dataset.

You only need **Game 1** and **Game 2** from the Metrica Sports sample tracking data.

Official source:  
http://metrica-sports.com/

Download the tracking CSV files for:
- Sample Game 1
- Sample Game 2


## Preparing the data

1. Download the tracking data for **Game 1** and **Game 2** from Metrica Sports  
2. Place all downloaded CSV files into the `data/` folder  

No additional datasets are required.



## Detail on how to run the code:

1. Make sure all Game 1 and Game 2 tracking CSV files are inside the `data` folder  
2. Open the Jupyter notebook provided in the repository  
3. Run all the cells in order  

The code will:
- Compute player speed from tracking data  
- Calculate team intensity as mean player speed  
- Detect substitution events  
- Compute the Substitution Value Score (SVS)  
- Generate plots showing intensity changes before and after substitutions
