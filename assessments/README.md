# Assessment Data

This directory holds the certified assessments for each tax year since 2014. The data can be loaded using [pandas](https://pandas.pydata.org):

```python
import pandas as pd
df = pd.read_json("2014.json.gz")
```

The columns descriptions are:

- **total_value**: the total assessed value as determined by the OPA
- **building_value**: the building portion of the assessed value
- **land_value**: the land portion of the assessed value
- **has_abatement**: whether the property has a valid 10-year tax abatement
- **is_condo**: whether the property is a condominium
- **total_area**: the total land area of the property in square feet
- **sale_date**: the date of the most recent sale for the property
- **sale_price**: the price of the most recent sale for the property
- **valid_sale**: whether the sale is reflective of market value, after being reviewed by the OPA
- **opa_zone**: the geographic zone that the property falls into
- **x**: the normalized x coordinate of the property in arbitrary units
- **y**: the normalized y coordinate of the property in arbitrary units
