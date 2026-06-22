DATA SOURCES AND DESCRIPTION:
For this project I have combined four publicly available datasets which are combined to construct the modeling corpus. The four datasets link are given below
1.	https://www.kaggle.com/datasets/ahmedshahriarsakib/usa-real-estate-dataset
2.	https://www.kaggle.com/datasets/polartech/500000-us-homes-data-for-sale-properties  
3.	https://www.kaggle.com/datasets/kanchana1990/new-york-real-estate-data-2026
4.	http://www.kaggle.com/datasets/jahnavikachhia23/texas-residential-real-estate-intelligence-2026 
## Datasets Used in This Study

| Dataset Name | Size | States | Key Columns Used | Has Description? | Role |
|-------------|------|---------|------------------|------------------|------|
| SAKIB (ahmedshahriarsakib) | 2.2M rows × 10 cols | All 50 States (TX + NY extracted) | price, bed, bath, house_size, acre_lot, state, status | No | TX + NY structured data backbone |
| POLARTECH (polartech) | ~500K rows × 28 cols | All 50 States (TX + NY extracted) | price, bedrooms, bathrooms, sqft, state, city | No | TX + NY structured data supplement |
| TEXAS 2026 (jahnavikachhia23) | ~12K rows × 13 cols | Texas (TX) only | description, price, sqft, bedrooms, bathrooms, home_type | Yes | NLP profile source for Texas |
| NEW YORK 2026 (kanchana1990) | ~9K rows × 11 cols | New York (NY) only | description, price, sqft, beds, baths, status | Yes | NLP profile source for New York |
