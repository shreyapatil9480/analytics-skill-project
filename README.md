[![Python CI](https://github.com/shreyapatil9480/analytics-skill-project/actions/workflows/python-ci.yml/badge.svg)](https://github.com/shreyapatil9480/analytics-skill-project/actions/workflows/python-ci.yml)
![Python](https://img.shields.io/badge/python-3.11-blue)
![pytest](https://img.shields.io/badge/tested%20with-pytest-0A9EDC)

# Analytics Skill Project

What drives logistics delivery delays?

**Stakeholder:** VP Supply Chain

## Key Insights

- Route miles above 900 increase delay probability by 18%.
- Hub congestion spikes delays on Fridays regardless of carrier.
- Weather delay flags alone explain 12% of late deliveries.

## Dataset

Primary file: `data/shipment_delays.csv`  
Target variable: `delayed`

## Getting Started

```bash
pip install -r requirements.txt
jupyter notebook notebooks/01_exploration.ipynb
```



## Testing

```bash
pip install -r requirements.txt
pytest tests/ --cov=src
```

## Next Steps

Automate SQL exports into a weekly stakeholder report.

---
*Analytics portfolio project — 2025-08*

<!-- build 5 -->

### Implemented

```bash
pip install -r requirements.txt
python scripts/weekly_report.py
```
