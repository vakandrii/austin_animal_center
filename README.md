# Austin Animal Center EDA

The goal of this exploratory data analysis project is to gain insights into the intake, outcomes, and characteristics of 
animals at the Austin Animal Center. By analyzing the provided datasets (`intakes.csv`, `outcomes.csv` and `locations.csv`),
the project aims to:

- Understand patterns and trends in animal intakes and outcomes over time.
- Investigate relationships between intake types, outcome types, and other animal attributes.
- Identify factors influencing adoption rates and outcomes for animals in the shelter.
- Generate descriptive statistics and visualizations to communicate findings effectively.

## Dataset Overview

Dataset [intakes](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Intakes/wter-evkm) 
contains data on animals admitted from 1 October 2013 to 27 April 2022. Dataset [outcomes](https://data.austintexas.gov/Health-and-Community-Services/Austin-Animal-Center-Outcomes/9t4d-g238)
contains data on animals that left the shelter (e.g. adopted, returned to owner, etc.) during the same time interval. It 
may be the case that animals admitted before 1 October 2013 do not appear in `intakes.csv` (data has not yet been 
collected), but will have an entry in `outcomes.csv` if they left the shelter after that date.

The `locations.csv` dataset provides information on all stray cats and dogs that have been in the shelter database for 
**less than a week**. Most are at the shelter, but some are with volunteers - this information is listed in the At AAC 
(Austin Animal Center) column.

## Project Structure
The project is organized as follows:
- `intakes.csv`: Dataset in csv format
- `outcomes.csv`: Dataset in csv format
- `locations.csv`: Dataset in csv format
- `README.md`: This file providing an overview of the project (You are reading it right now!).
- `animal_center.ipynb`: Jupyter Notebook containing the code for data preprocessing, EDA, generating descriptive 
                         statistics and visualizations and addressing custom analytical questions with visualizations.
- `requirements.txt`: List of Python packages required to run the notebook.

## Setup and Usage
1. **Setup**
   - Clone this repository to your local machine.
      ```bash
      git clone https://github.com/your_username/your_repository.git
      ```
   - Navigate to the project directory.
   - Install the required Python packages using pip:
     ```bash
     pip install -r requirements.txt
     ```
   - Launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - Open `animal_center.ipynb` in your browser.

## Acknowledgment
I extend my heartfelt gratitude to the Austin Animal Center for generously providing the dataset and to the city of Austin 
for making this data openly accessible. I sincerely appreciate the efforts of everyone involved in collecting and 
maintaining this dataset. Thank you!