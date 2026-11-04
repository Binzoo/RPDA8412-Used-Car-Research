# Used Car Segmentation and Price Prediction in South Africa

Code for the RPDA8412 research project: "A Hybrid Machine Learning Framework for Segment Classification and Price Prediction in the South African Used Car Market".

Author: Binamra Thapa (ST10090477)
Supervisor: Dr Moses Olaifa
The Independent Institute of Education

## Contents
`RPDA8412_Analysis.ipynb` contains the full analysis and its results: data cleaning, clustering, price prediction, feature importance and provincial analysis.

## Data
The scraped data is not included in this repository. It was collected in May 2026 from WeBuyCars and Cars.co.za and was not shared with third parties.

## Running the notebook
The notebook expects these five files in a folder called `data`:

- `wc_cars.csv`
- `cars_kzn_cars.csv`
- `kzn_cars_webuycars.csv`
- `carsco_cars.csv`
- `johannesburg_cars_webuy-cars.csv`

It uses Python 3.11. The packages not usually preinstalled are installed in the first code cell.
