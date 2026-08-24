# SCDisrupt-Synth
Synthetic benchmark dataset for supply chain disruption early-warning research
DOI: https://doi.org/10.5281/zenodo.22073886
# SCDisrupt-Synth

SCDisrupt-Synth is a fully synthetic multi-source benchmark dataset for supply chain disruption early-warning research using Natural Language Processing and machine learning.

## Dataset DOI

https://doi.org/10.5281/zenodo.22073886

## Dataset overview

The dataset contains:

- 2,400 source-level records
- 600 prediction windows
- 4 source types:
  - News
  - Social media
  - Supplier communications
  - Financial reports
- 12 industry sectors
- Positive and negative disruption scenarios
- Train, validation, and test splits

The dataset is fully synthetic and contains no proprietary company data, confidential supplier information, customer information, or personal data.

## How to use

```python
import pandas as pd

df = pd.read_csv("scdisrupt_synth_v1.csv")

print(df.head())
print(df.shape)
