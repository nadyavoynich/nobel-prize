# Nobel Prize: A Deep Dive into 120 Years of Celebrated Achievements
<img src=https://i.imgur.com/36pCx5Q.jpg>

## Project Description
On November 27, 1895, Alfred Nobel signed his last will in Paris.
When it was opened after his death, the will caused a lot of controversy, as Nobel had left much of his wealth for the establishment of a prize.
Alfred Nobel dictates that his entire remaining estate should be used to endow “prizes to those who, during the preceding year, have conferred the greatest benefit to humankind”.
Every year the Nobel Prize is given to scientists and scholars in the categories chemistry, literature, physics, physiology or medicine, economics, and peace.

The primary aim of this project is to identify trends within the data related to former Nobel laureates:
* What trends emerge when analyzing data on past Nobel laureates?
* What insights can the Nobel Prize offer about our world at large?

**Main questions to answer:**
1. Gender distribution among the laureates: Male vs. Female.
2. Who are the multiple-time recipients of the award?
3. How many prizes were awarded over time and across categories?
4. Which countries and research organizations have garnered the most Nobel Prizes?
5. What are the patterns in the laureate age at the time of the award?

## Dataset Overview
### Source
"100 Days of Code: The Complete Python Pro Bootcamp for 2023", by Dr. Angela Yu

### Dataset structure
The dataset comprises a .csv file:
* `nobel_prize_data.csv` covering the years from 1901 through 2020 (16 attributes, 962 entries).

## Setup & Requirements
Follow these steps to get the data analysis project up and running on your local machine.

### Prerequisites
1. **Python**: This project requires Python 3.9 or higher.
If you don't have Python installed, [download and install](https://www.python.org/downloads/) the latest version.
2. **Jupyter Notebook**: Jupyter Notebook is used for the interactive analysis. If you don't have it, install it using pip:
``pip install jupyter``

### Setting Up a Virtual Environment (Recommended)
It's recommended to set up a virtual environment to avoid any package conflicts.
1. Install `virtualenv` if not installed: ``pip install virtualenv``
2. Navigate to the project directory and create a virtual environment: ``virtualenv venv``
3. Activate the virtual environment:
    - **Windows**: ``.\\venv\\Scripts\\activate``
    - **macOS/Linux**: ``source venv/bin/activate``

### Installing Required Libraries
With the virtual environment activated, install the necessary libraries using:
``pip install -r requirements.txt``

Python libraries used:
* pandas
* numpy
* seaborn
* plotly
* matplotlib

### Getting the Data
This project uses the `Nobel Prize` dataset.
1. Download the dataset from the project repository.
2. Place the downloaded dataset in the same directory.

### Running the Notebook
With everything set up, start the Jupyter Notebook server: ``jupyter notebook``
Navigate to the desired notebook and you're ready to start your analysis!

## Methodology
* Exploratory data analysis
* Descriptive statistics
* Time series analysis

## Findings & Conclusions
#### Gender distribution
* Out of all the Nobel laureates only about 6.2% were women. 
* Together with that women are somewhat more represented in categories of medicine, literature and peace.
#### Multiple-time laureates
* There are 6 winners who were awarded the prize more than once, 4 of them were individuals, including Marie Skłodowska-Curie.
She was the first woman to win a Nobel Prize, the first person to win a Nobel Prize twice, and the only person to win 
a Nobel Prize in two scientific fields.
* The International Committee of the Red Cross was awarded 3 times: in 1917, 1944, and 1963.

#### Number of prizes over time
* Over the course of 120 years, 962 Nobel Prizes have been awarded.
* Out of 6 categories, medicine category has the most number of prizes awarded, while Economics category has the fewest number.
This is connected with te fact that the economics prize was first awarded only in 1969.
* There is clearly an upward trend in the number of prizes being given out as more and more prizes are shared.
A very few prizes were awarded during the first and second world wars.

#### Geography and top research organizations
* The United States is ranked number 1 measured by the number of prizes.
The US has 2.7 times more prizes compared to the rank #2, which is placed by the United Kingdom, the top country in Europe by this measure.
* The United States experienced significant growth after the Second World War, a period that had devastated Europe.
Before that, the Nobel Prize was primarily a European endeavor, with only a handful of laureates selected from other regions.
* The absolute leader among research organizations is the University of California with 40 prizes.
* Cambridge (MA) and New York in the United States are the number one hotspot for discoveries in the world.

#### Laureate age
* John Goodenough from Germany was 97 years old when he got the Nobel Prize and 
Malala Yousafzai from Pakistan was awarded when she was only 17 years old.
* The average age of a winner is around 60 years.
75% of laureates are younger than 69 years old when they receive the prize.
* Moving average represents that the Nobel laureates are getting their award later and later in life.
At the same time in the last 10 years the spread has increased. We've had more very young and very old winners.
* Winners in physics, chemistry, and medicine have gotten older over time.
The peace prize shows the opposite trend where winners are getting younger.
Economics, the newest category, is much more stable in comparison.