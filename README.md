## Nobel Prize Data Analysis

!['Award'](Award.jpg)

The Nobel Prizes are awards administered by the Nobel Foundation and granted in accordance with the principle of "for the greatest benefit to humankind". The prizes were first awarded in 1901 ( [Wikipedia](https://en.wikipedia.org/wiki/Nobel_Prize) )

**Note**: the scope of this project is related to the Nobel prize dataset, the dataset years awards up to the year 2023.


## Project scope

**The project aims to answer the following questions** : 

* What is the proportion of female and male Nobel Prize laureates?
* What are the top 5 countries by number of Nobel Prize laureates?
* What is the category-wise distribution (value count) of Nobel Prize laureates for each of the top 5 countries?
* For each of the top 5 countries by Nobel Prize laureates, identify the year with the highest percentage of laureates from that country.
* Who are the top 5 individuals who have won the most Nobel Prizes?
* Which organization has been awarded the most Nobel Prizes?

## Approach

The project can be divided into 5 main phases: 

- **Phase 1 Installing dependencies** : Only popular python packages were used in the project, this helps lower the risk of accidentally installing malware.
- **Phase 2 Loading Data** : data was loaded into a pandas DataFrame.
- **Phase 3: Exploratory Data Analysis**: in this phase tasks related to exploring the data was conducted such as calculating General Statistics about the data, calculating null values and searching for duplicate values.
- **Phase 4: Data preparation & Cleaning**: in this phase i did some tasks like replacing null values of **birth_date** column and adding  **birth_decade** column that will help answer one of the question mentioned in project score.
- **Phase 5: Insight Extraction**: in this phase i answer the questions mentioned in the project scope.


## Insights

### The proportion of female and male Nobel Prize laureates

<img width="559" height="580" alt="image" src="https://github.com/user-attachments/assets/ecf47455-740d-47b2-ab0a-77e2a785ebba" />

---

### The top 5 countries with the most nobel prize laureates

<div>
<table border="1" class="dataframe">
  <thead>
    <tr style="text-align: right;">
      <th>Birth Country</th>
      <th>Laureates Count</th>
    </tr>

  </thead>
  <tbody>
    <tr>
      <th>United States of America</th>
      <td>291</td>
    </tr>
    <tr>
      <th>United Kingdom</th>
      <td>91</td>
    </tr>
    <tr>
      <th>Germany</th>
      <td>86</td>
    </tr>
    <tr>
      <th>France</th>
      <td>61</td>
    </tr>
    <tr>
      <th>Sweden</th>
      <td>30</td>
    </tr>
  </tbody>
</table>
</div>

---

### Prize category value count for the top 5 countries by laureate count

<img width="1034" height="651" alt="image" src="https://github.com/user-attachments/assets/08db7b44-81cd-47e4-a910-a7d1670a57ba" />

**Observation**:

**USA** has the highest number of nobel prize laureats in each category except for the **Literature category**, as **France** has the highest number of Nobel prize for literature laureats

---

### The years with the highest percentage of laureates from each of the top 5 countires

* **USA** : 1946
* **UK** : 1932
* **France**: 1912
* **Germany**: 1918
* **Sweden**: 1916

---

### The top 5 individuals who have won the most Nobel Prizes


Each of following laureates won 2 Nobel prizes : 

* Marie Curie, née Sklodowska
* Linus Carl Pauling
* John Bardeen
* Frederick Sanger
* K. Barry Sharpless
* Barry Sharpless

---

### Which organization has been awarded the most Nobel Prizes?

- **International Committee of the Red Cross** won 3 Nobel prizes



