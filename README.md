### General Methods 
#### Read
- `pd.read_csv('ANY.csv')`
- `pd.DataFrame.from_dict`
- `ANY_DATAFRAME.head()`
- `ANY_DATAFRAME.tail()`
- `ANY_DATAFRAME.iloc[row, index]`

#### Filtering
- `df['ANY_FEATURE']`
- `df[['ANY_FEATURE', 'ANY_FEATURE1']]`
- `df['ANY_FEATURE'].unique()`
- `df[df['ANY_FEATURE']==CONDITION]`
- `df[(df['ANY_FEATURE']=='CONDITION') & (df['ANY_FEATURE1']==CONDITION1)]`


#### Update
- `df.drop('ANY_FEATURE', axis=1)`
- `df['ANY_CALCULATED_COLUMN'] = df['ANY_FEATURE'] + df['ANY_FEATURE1']`
- `df['ANY_FEATURE'] = ANY_VALUE`

#### File Management
- `df.to_csv('output.csv')`

#### JSON/HTML
- `df.to_json()`
- `df.to_html()`

### Helpers
You can press `tab` to bring up autocomplete.