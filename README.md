## New Mexico - Bernalillo COVID-19 Predictor

This project pulls data from official NM DOH COVID-19 API for Bernalillo County, plots it prettily,
and analyzes the data to determine the current phase at which  Bernalillo Colunty should be within
New Mexico's [Red-to-Green Framework](https://cv.nmhealth.org/public-health-orders-and-executive-orders/red-to-green/).

Run by setting up Python 3 and PIP, then running the following commands
(note you may need to substitute `pip3` for `pip`):

```bash
pip install -r requirements.txt
jupyter lab new-mexico-covid-19-predictor.ipynb
```