# lapd-crime-analysis

Exploratory data analysis of LAPD crime data, identifying patterns in crime timing, location, and victim demographics across Los Angeles.

## What this covers

- Peak hour of crime across the full dataset
- Areas with the highest volume of night-time crime (10pm–3:59am)
- Breakdown of crimes by victim age group

## Project structure

```
├── notebook.ipynb    # Main analysis notebook
├── crimes.csv        # Dataset
├── requirements.txt  # Python dependencies
└── README.md
```

## Dataset

The analysis uses `crimes.csv`, a modified version of the publicly available LAPD crime dataset from [Los Angeles Open Data](https://data.lacity.org/).

| Column | Description |
|--------|-------------|
| `DR_NO` | Official file number |
| `Date Rptd` | Date reported |
| `DATE OCC` | Date of occurrence |
| `TIME OCC` | Time of occurrence (24-hour) |
| `AREA NAME` | LAPD patrol division |
| `Crm Cd Desc` | Crime description |
| `Vict Age` | Victim age |
| `Vict Sex` | Victim sex |
| `Vict Descent` | Victim descent code |
| `Weapon Desc` | Weapon used (if applicable) |
| `Status Desc` | Crime status |
| `LOCATION` | Street address |

## Getting started

```bash
git clone https://github.com/maarufvai/lapd-crime-analysis.git
cd lapd-crime-analysis
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```

## Requirements

Python 3.7+ and the packages in `requirements.txt`.
