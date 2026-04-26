  # Experiment-20
  ## Aim of Experiment: 
  Covid Data Analysis
  ## Theory:
  Data analysis is the process of inspecting, cleaning, transforming, and visualizing raw data in order to extract meaningful insights.  
  COVID-19 data analysis became one of the most important real-world applications of data science. By analyzing confirmed cases, deaths, recoveries, and active cases,
  governments and researchers can understand the spread of disease and take informed decisions.This experiment uses a large COVID dataset containing global records
  from 22 January 2020 to 29 May 2021 with more than 306,000 entries.  
  ## Libraries used are:
  1.Pandas → Data cleaning, filtering, grouping, aggregation  
  2.NumPy → Numerical operations  
  3.Plotly Express → Interactive choropleth maps  
  4.JSON / urllib → Loading India GeoJSON map data 
  ## Commands and functions used in experiment:
- Performs COVID-19 data analysis and visualization using Python
- Loads dataset using pd.read_csv("file_path")
- Displays initial data using data.head()
- Checks structure using data.info()
- Removes unnecessary columns using data.drop(['SNo','Last Update'], axis=1)
- Converts data types using data.astype('datatype')
- Handles missing values using fillna("value")
- Creates new column using data['NewColumn'] = ...
- Selects rows using data.iloc[start:end]
- Finds maximum values using data['column'].max()
- Gets dataset size using data.shape
- Filters data using data[data['column'] == value]
- Groups and aggregates data using groupby("column")[['col1','col2']].sum()
- Resets index using reset_index()
- Counts occurrences using value_counts()
- Finds unique values using unique()
- Counts unique values using nunique()
- Sorts data using sort_values(['column'], ascending=False)
- Calculates active cases using Active = Confirmed - Recovered - Deaths
- Fetches GeoJSON data using urllib.request.urlopen(url)
- Loads GeoJSON using json.load(response)
- Creates choropleth maps using px.choropleth(...)
- Adjusts map using fig.update_geos()
- Customizes layout using fig.update_layout()
- Displays visualization using fig.show()
- Performs country-wise and state-wise analysis
- Extracts latest date data and computes totals
- Focuses on data cleaning, transformation, and visualization workflow
## Conclusion:
- Demonstrates complete workflow of data cleaning, processing, and analysis using Python.  
- Provides interactive visualization of COVID-19 data using maps for better insights.  
  
