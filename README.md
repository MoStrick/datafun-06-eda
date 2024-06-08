# datafun-06-eda

### The purpose of this project is to

### Create files


### Import Dependencies/ Requirements.txt
'''sh
pip install jupyterlab

pip install -r requirements.txt
pip freeze > requirements.txt


### Extensions
VS Code Jupyter Notebook Previewer
Rainbow CSV



### Terminal Commands

# Exploratory Data Analysis
### Step 1: Data Acquisition
The data can be found at [Taxis Data](https://github.com/mwaskom/seaborn-data/blob/master/taxis.csv)

Load the dataset into a pandas DataFrame - adjust this process for your custom data
df_taxis = sns.load_dataset('iristaxis')

Inspect first 5 rows of the DataFrame
print(df.head(5))

### Step 2:  Initial Data Inspection

print(df.head(10))
print(df.shape)
print(df.dtypes)

### Step 3: Initial Descriptive Statistics

print(df.describe())


Step 4: Initial Data Distribution for Numerical Columns
Step 5. Initial Data Distribution for Categorical Columns
Step 6. Initial Data Transformation and Feature Engineering
Step 7. Initial Visualizations
Step 8. Initial Storytelling and Presentation
