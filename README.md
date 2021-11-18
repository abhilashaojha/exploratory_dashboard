# About

This is a basic interactive dashboard made using MS-Excel with dataset on Crime against women in India for
each district, every year since 2001, gathered from National Criminal Records Bureau (NCRB). 

We take a look at 15 states and 3 union territories and
compare the crime rate against women with
the help of exploratory data analysis.

We have used the tools available in MS-EXCEL to visualize the data in the
form charts and tables.

# Contributors
- Avishree Roy 
- Diksha Tripathi

# Overview of the dataset
We used the NCRB district-wise crime against
women data set. The data set consists of the
following attributes:
- **STATE:** The name of the state in India in
which the crime was committed.
- **DISTRICT:** The name of the district in the
state where the crime was committed.
- **YEAR:** The year in which these crimes
took place, having values from 2001 to 2013.
- **Rape:** The total number of Rape cases.
- **Kidnapping & Abduction:** The total
number of abduction or kidnapping cases.
- **Dowry Deaths:** The total number of Dowry
Deaths.
- **Assault on women with intent to outrage
her modesty:** The total number of cases in
this category.
- **Insult to modesty of Women:** The total
number of cases in this category. These
cases are separate to assault cases.
- **Cruelty by Husband or his Relatives:** The
total number of cases in this category.
- **Importation of girls:** The total number of
cases where girls had been imported from
elsewhere.


> There are about 9800 rows and the size of it is
approximately 467 KB. It contains data from the
year 2001 to 2013.

# Data Preprocessing
## Software Used:
For our preprocessing, we employ Microsoft Excel
and Python. 

The preprocessing stage used python libraries
like pandas and NumPy to figure out the total no.
of missing values to get an overview of the dataset
and to create correlation heat maps.

The implementation of the rest of the project that is
analysis in trends etc. has been done using Pivot
Tables and Charts provided by Excel.

# Data Cleaning
As we were working with a dataset with a large
number of values our attention first and foremost
fell to the fact of whether our dataset had any
missing values. 

With the help of pandas, we easily
found out whether our dataset had any missing
values.

A few columns have been added or
transformed to improve the result of the following
analysis. The decision to add or transform columns
has been taken by studying the graphical analysis
which has been performed on the data.

Like, the **ASSAULT ON WOMEN
WITH INTENT TO OUTRAGE HER MODESTY** changed to
**MOLESTATION**

# Data Transformation
The main transformations performed are as follows:
- Population of districts were added
according to the census taken in 2001 and 2011. Till 2010 the population was taken according to 2001 census after which the values were provided by the 2011 census.
- The Crime Rate was calculated according
to the formula provided in the first section
of design for or each district.
- Standardization of values was performed
so that each category had number of cases
per 100,000 persons.
- The number of columns was increased to
include these values.
- Further analysis was performed via these
new values and not the original values.

# Data Reduction
The original dataset consisted of 26 states and 7 union
territories. The total number of districts were over 358.  We worked on only 15 states and 3 union territories. The other states and union territories were removed from the dataset.

> This is was done so that it will easier to manage the
huge amount of data. This reduces the number of
rows from about 9800 to about 4965.


# Screenshot

![Dashboard](https://raw.githubusercontent.com/abhilashaojha/exploratory_dashboard/main/imgs/Dashboard.png)