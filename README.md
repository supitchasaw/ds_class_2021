- [2602454: Business Intelligence System](#2602454-business-intelligence-system)
  - [สื่อการสอน Python for Data Science บน YouTube:](#สื่อการสอน-python-for-data-science-บน-youtube)
  - [week 1: 20-Jan-2021](#week-1-20-jan-2021)
    - [intro to data science](#intro-to-data-science)
  - [week 2: 27-Jan-2021 (pandas)](#week-2-27-jan-2021-pandas)
    - [intro to pandas](#intro-to-pandas)
      - [Read data techniques](#read-data-techniques)
      - [Save data technique](#save-data-technique)
    - [Data selection](#data-selection)
    - [data types](#data-types)
    - [EDA](#eda)
    - [Missing values](#missing-values)
  - [week 3: 3-Feb-2021](#week-3-3-feb-2021)
    - [Announcement](#announcement)
    - [Filter](#filter)
    - [Merge, Join, Pivot](#merge-join-pivot)
  - [week 4: 10-Feb-2021](#week-4-10-feb-2021)
    - [mutable DataFrame](#mutable-dataframe)
    - [regular expression](#regular-expression)
    - [Web scraping](#web-scraping)
    - [Assignments](#assignments)
  - [week 5: 17-Feb-2021](#week-5-17-feb-2021)
    - [Announcement](#announcement-1)
    - [Web scraping](#web-scraping-1)
    - [labmda](#labmda)
    - [clean multilevel table](#clean-multilevel-table)
    - [Widget](#widget)
    - [EDA](#eda-1)
    - [matplotlib](#matplotlib)

---
# 2602454: Business Intelligence System
* github: https://github.com/prasertcbs/ds_class_2021
## สื่อการสอน Python for Data Science บน YouTube:  
- [ไพธอน Python เบื้องต้น](https://www.youtube.com/playlist?list=PLoTScYm9O0GEoKcXJ-C5NrywxpvATaoG1)
- [Jupyter Notebook](https://www.youtube.com/playlist?list=PLoTScYm9O0GErrygsfQtDtBT4CloRkiDx)
- [Jupyter Lab](https://www.youtube.com/playlist?list=PLoTScYm9O0GEour5CiwfSnoutg3RyA76O)
- [Pandas](https://www.youtube.com/playlist?list=PLoTScYm9O0GGsOHPCeufxCLt-uGU5Rsuj)
- [Seaborn](https://www.youtube.com/playlist?list=PLoTScYm9O0GGC9QvLlrQGvMYatTjnOUwR)
- [Numpy](https://www.youtube.com/playlist?list=PLoTScYm9O0GFNEpzsCBEnkUwgAwOu_PWw)
- [Matplotlib](https://www.youtube.com/playlist?list=PLoTScYm9O0GGRvUsTmO8MQUkIuM1thTCf)
- [scikit learn](https://www.youtube.com/watch?v=AdDvPCarDyI&list=PLoTScYm9O0GH_3VrwwnQafwWQ6ibKnEtU)
- [การใช้ git และ github](https://www.youtube.com/playlist?list=PLoTScYm9O0GGsV1ZAyP4m_iyAbflQrKrX)
## week 1: 20-Jan-2021
### intro to data science
  * [x] [CRISP model: CRoss-Industry Standard Process for data mining](https://en.wikipedia.org/wiki/Cross-industry_standard_process_for_data_mining#/media/File:CRISP-DM_Process_Diagram.png)
  * [x] [machine learning](https://jakevdp.github.io/PythonDataScienceHandbook/05.01-what-is-machine-learning.html)
  * [x] TARGET teenage pregnancy case 2012
    * [x] [New York Times](https://www.nytimes.com/2012/02/19/magazine/shopping-habits.html)
    * [ ] [Forbes](https://www.forbes.com/sites/kashmirhill/2012/02/16/how-target-figured-out-a-teen-girl-was-pregnant-before-her-father-did/?sh=5199355b6668)
    * [ ] [video clip](https://nyti.ms/2kH3YzT)
  * [ ] [Netflix: the social dilemma](https://www.netflix.com/th-en/title/81254224)
  * [ ] [Netflix: the great hack](https://www.netflix.com/th-en/title/80117542)
* [ ] explore data
  * [x] sample data:
    * [x] [bigmac index](./bigmac_index.csv)
    * [x] [telecom customer churn](./Telco-Customer-Churn.csv)
    * [ ] [food nutrition](./nutrients.csv)
  * [x] pandas vs sql
    * [x] [pandas](https://www.youtube.com/watch?v=f3CLdRl-zyQ&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz)
* [ ] packages
  * [ ] installation: 
    * [ ] `conda install pandas numpy seaborn matplotlib scikit-learn`
    * [ ] `pip install -U pandas numpy seaborn matplotlib scikit-learn`
  * [ ] [JupyterLab](https://www.youtube.com/watch?v=3PkMNsUCAM0&list=PLoTScYm9O0GEour5CiwfSnoutg3RyA76O)
  * [ ] [learn pandas](https://www.youtube.com/watch?v=f3CLdRl-zyQ&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz)
  * [ ] [learn numpy](https://www.youtube.com/watch?v=ts2L5mtMMi8&list=PLoTScYm9O0GFNEpzsCBEnkUwgAwOu_PWw)
  * [ ] [learn matplotlib](https://www.youtube.com/watch?v=WOEOH8OV99k&list=PLoTScYm9O0GGRvUsTmO8MQUkIuM1thTCf)
  * [ ] [learn seaborn](https://www.youtube.com/watch?v=TJ2xK3AV5RQ&list=PLoTScYm9O0GGC9QvLlrQGvMYatTjnOUwR)
  * [ ] [learn scikit-learn](https://www.youtube.com/watch?v=AdDvPCarDyI&list=PLoTScYm9O0GH_3VrwwnQafwWQ6ibKnEtU)
* [ ] how to use github repository
  * [ ] [basic github](https://www.youtube.com/watch?v=hSQgAA8bj6I&list=PLoTScYm9O0GGsV1ZAyP4m_iyAbflQrKrX)
* [ ] recommended resources:
  * [x] [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)
    * [ ] [Jupyter Notebook on github](https://github.com/jakevdp/PythonDataScienceHandbook)
    * [ ] [pandas documentation](https://pandas.pydata.org/docs/)
    * [ ] [Kaggle](https://www.kaggle.com/)
    * [ ] [Stack Overflow](https://stackoverflow.com/)
---
## week 2: 27-Jan-2021 (pandas)
### intro to pandas
#### [Read data techniques](https://www.youtube.com/watch?v=fNJb52eMLNg&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=97)
* [x] separator
* [x] nrows
* [x] parse_dates
* [x] sample
* [x] transpose
* [x] read_html
#### Save data technique
* [x] csv
* [x] Excel
* [ ] [display options](https://pandas.pydata.org/pandas-docs/stable/user_guide/options.html)
  * [ ] max rows
    * `pd.set_option('display.max_rows', None)` 
  * [ ] max cols
    * `pd.set_option('display.max_columns', None)`
### Data selection
* [x] [Series](https://www.youtube.com/watch?v=dX6COdB7yRo&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=22)
  * [x] index (as dictionary), slice
* [x] [DataFrame](https://www.youtube.com/watch?v=NrcAJFJo1R4&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=23)
  * [x] index, slice
  * [x] [loc](https://www.youtube.com/watch?v=k5rjyOhG3kg&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=74)
  * [ ] [iloc](https://www.youtube.com/watch?v=2mRwQ2_p0Ws&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=76)
### data types
* [x] number (int, float)
* [x] object
  * [x] [to_numeric](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_numeric.html)
* [ ] [category](https://youtu.be/ulDIl1E_VVA)
  * [ ] astype('category')
* [x] [datetime](https://youtu.be/Zfp5YVZtwYc)
  * [x] [to_datetime](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_datetime.html)
### EDA
* [x] describe()
* [ ] aggregate functions
* [x] correlation
* [x] visualizing data
  * [x] histogram
  * [x] boxplot
  * [x] scatterplot
### Missing values
* [x] [sample data](https://github.com/prasertcbs/basic-dataset/raw/master/msleep.csv)
* [ ] [clip 1](https://youtu.be/Ysgqv1ICWU4)
* [ ] [clip 2](https://youtu.be/Fib0R8yJOYE)

---
## week 3: 3-Feb-2021
### Announcement
* [x] Quiz 1 (35 points) on 24-Feb-2021
* [x] Internship
### Filter
* [ ] ==, !=, <, >, ~, &, |
* [x] [regular expression](https://www.youtube.com/watch?v=KTGvdg9c_qU&list=PLoTScYm9O0GHsd-2JwUcifFTO3EuqJB4F)
### Merge, Join, Pivot
* [ ] [concat](https://www.youtube.com/watch?v=fNJb52eMLNg&list=PLoTScYm9O0GFVfRk_MmZt0vQXNIi36LUz&index=97) (combine) DataFrames
  * [ ] append rows
    * [ ] [michelin restaurants](https://github.com/prasertcbs/basic-dataset/tree/master/michelin%20restaurants)
* [ ] merge DataFrames
  * [ ] covid exam
* [ ] crosstab, pivot
## week 4: 10-Feb-2021
### mutable DataFrame
* [ ] deep copy
  * [x] [Chiang rai temperature](https://th.wikipedia.org/wiki/%E0%B8%88%E0%B8%B1%E0%B8%87%E0%B8%AB%E0%B8%A7%E0%B8%B1%E0%B8%94%E0%B9%80%E0%B8%8A%E0%B8%B5%E0%B8%A2%E0%B8%87%E0%B8%A3%E0%B8%B2%E0%B8%A2)
### [regular expression](https://www.youtube.com/watch?v=KTGvdg9c_qU&list=PLoTScYm9O0GHsd-2JwUcifFTO3EuqJB4F&index=1)
* [x] [parse_reg_chula_roster.ipynb](parse_reg_chula_roster.ipynb)
* [x] [data cleansing](regex_clean_data_chiangrai_temperature.ipynb)
* [x] [regex101.com](https://regex101.com/)
* [ ] [import re](https://docs.python.org/3/library/re.html)
  * [ ] re.sub
    * [ ] remove non-digit
    * [ ] re.sub(r'\D', '', '$1,234')
    * [ ] re.sub(r'[^\d\.]', '', '$1,234')
  * [ ] re.findall("\'(.+)\'", "hello 'thailand' 4.0")[0]
* [x] Series.str
* [ ] examples
  * [ ] [rai-ngan-wah](https://github.com/prasertcbs/basic-dataset/raw/master/area_conversion.xlsx)
  * [ ] [geo:lat,lon](https://github.com/prasertcbs/basic-dataset/raw/master/temple_geo.tsv)
  * [ ] [pixar quiz](https://github.com/prasertcbs/basic-dataset/raw/master/regexp_extract_split.csv)
  * [ ] [explode list](https://youtu.be/9OUwRrshD1s)
  * [ ] [get_dummies](https://youtu.be/4d5XZAsV-sw)
### [Web scraping](https://www.youtube.com/watch?v=Y-_t5Hll09I&list=PLoTScYm9O0GHM1yuswgoL6tUcMge7FwP7)
* [x] [Liverpool FC](https://www.liverpoolfc.com/team/first-team)
### Assignments
* [ ] [Web scraping](https://www.youtube.com/watch?v=Y-_t5Hll09I&list=PLoTScYm9O0GHM1yuswgoL6tUcMge7FwP7)
  * [ ] scrape an interesting website and save scraped data as CSV

## week 5: 17-Feb-2021
### Announcement
* [ ] Quiz 1: regex & web scraping (35 points, 2 hours)
  * [ ] zoom user: student_id first_name last_name
### [Web scraping](https://www.youtube.com/watch?v=Y-_t5Hll09I&list=PLoTScYm9O0GHM1yuswgoL6tUcMge7FwP7)
* [ ] [Liverpool FC](https://www.liverpoolfc.com/team/first-team)
  * [ ] [notebook](example/webscraping_liverpool_fc.ipynb)
  * [ ] [YouTube](https://www.youtube.com/watch?v=Y-_t5Hll09I&list=PLoTScYm9O0GHM1yuswgoL6tUcMge7FwP7&index=1)
  * [ ] HTML + image
  * [ ] HTML table to Excel
### labmda
* [ ] [python lambda](https://www.youtube.com/playlist?list=PLoTScYm9O0GHJQXNPKP34Cu7unIxa17B9)
* [ ] [pandas lambda](https://www.youtube.com/watch?v=GRYfWdJ_46k&list=PLoTScYm9O0GHybs6sQKhFLhLUPDDHpBcQ)
  * [ ] [example](example/why_lambda.ipynb)
  * [ ] [map](https://youtu.be/RQYyPAJuoX8)
  * [ ] [apply](https://youtu.be/3vZocRESZF4)
  * [ ] [applymap](https://youtu.be/TCN5t-TIosM) 
### [clean multilevel table](https://youtu.be/3PZO2gp6FqY)
* [ ] [starbucks menu](https://github.com/prasertcbs/pandas/blob/main/pandas_clean_multilevel_table.ipynb)
### [Widget](https://www.youtube.com/watch?v=_YrB8JblQz8&list=PLoTScYm9O0GEour5CiwfSnoutg3RyA76O&index=12)
* [ ] [McDonald](example/interactive_ipywidgets.ipynb)
### [EDA](https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e)
> source: https://towardsdatascience.com/an-extensive-guide-to-exploratory-data-analysis-ddd99a03199e  
> ‘Understanding the dataset’ can refer to a number of things including but not limited to…  
> * [ ] `Extracting` important variables and leaving behind useless variables
> * [ ] `Identifying` outliers, missing values, or human error
> * [ ] `Understanding` the relationship(s), or lack of, between variables
> * [ ] `Maximizing` your insights of a dataset and minimizing potential error that may occur later in the process
### [matplotlib](https://www.youtube.com/watch?v=WOEOH8OV99k&list=PLoTScYm9O0GGRvUsTmO8MQUkIuM1thTCf)
* [ ] subplots r x c