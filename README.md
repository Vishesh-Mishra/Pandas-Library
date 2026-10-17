# Pandas Notebook

A complete, hands-on notebook covering the **Pandas** library in Python, from the basics of Series and DataFrames to GroupBy, Merge, MultiIndex, Pivot Tables, string operations and time series. Every concept is practiced with real datasets (IPL, IMDB, Titanic, COVID-19, expenses and more).

## Topics Covered

1. **Pandas Series**
   - Creating a Series from lists, dictionaries and `read_csv`
   - Attributes: `size`, `dtype`, `name`, `is_unique`, `index`, `values`
   - Methods: `head`, `tail`, `sample`, `value_counts`, `sort_values`, `sort_index`
   - Math methods: `count`, `sum`, `mean`, `median`, `mode`, `std`, `var`, `min`, `max`, `describe`
   - Indexing, slicing, fancy indexing and editing a Series
   - Boolean indexing and plotting graphs on a Series

2. **Pandas DataFrame**
   - Creating DataFrames from lists, dictionaries and CSV files
   - Attributes and methods: `shape`, `dtypes`, `columns`, `info`, `describe`, `isnull`, `duplicated`, `rename`
   - Selecting columns and rows using `iloc` and `loc`
   - Filtering with boolean indexing and adding new columns
   - `astype` for memory optimization

3. **Important Functions**
   - `between`, `clip`, `drop_duplicates`, `isin`, `apply`, `copy`
   - `sort_values`, `sort_index`, `set_index`, `reset_index`, `rename`
   - `unique`, `nunique`, `isnull`, `notnull`, `dropna`, `fillna`, `ffill`, `bfill`, `drop`

4. **GroupBy**
   - Aggregation functions, `agg`, `apply` and looping on groups
   - GroupBy on multiple columns

5. **Merging and Joining**
   - `concat` (vertical and horizontal)
   - `merge`: inner, left, right, outer and self join
   - 10 practice questions on a students and courses registration dataset

6. **MultiIndex**
   - MultiIndex Series and DataFrames
   - `stack`, `unstack`, `swaplevel`, `transpose`
   - Selecting and sorting on a MultiIndex

7. **Reshaping Data**
   - Long vs Wide format using `melt`
   - `pivot_table` with `aggfunc`, `margins` and `fill_value`

8. **Vectorized String Operations**
   - `.str` accessor: `upper`, `lower`, `split`, `strip`, `replace`, `contains`, `startswith`, slicing
   - Regular expressions on the Titanic dataset

9. **Time Series**
   - `Timestamp`, `DatetimeIndex`, `date_range`, `to_datetime`
   - `.dt` accessor and plotting date-wise expense data

## Datasets Used

- IPL matches and deliveries
- IMDB Top 1000 movies and Bollywood movies
- Virat Kohli IPL runs and YouTube subscribers
- Titanic
- COVID-19 global confirmed cases and deaths
- Personal expense data
- Seaborn `tips` dataset
- Students, courses and registration data

> **Note:** The CSV files are loaded from my local machine. To run the notebook, download the datasets and change the file paths in the `pd.read_csv()` lines.

## Libraries Used

- pandas
- numpy
- matplotlib
- seaborn

## How to Run

1. Clone this repository
   ```
   git clone <your-repo-link>
   ```
2. Install the required libraries
   ```
   pip install pandas numpy matplotlib seaborn jupyter
   ```
3. Open the notebook
   ```
   jupyter notebook pandas.ipynb
   ```

## Author

**Vishesh**
B.Tech CSE (3rd Year)

This notebook is part of my Machine Learning learning journey (NumPy → Pandas → ...).

