![image](https://user-images.githubusercontent.com/101889306/181923228-eaf792aa-cfdb-4aae-bc56-17904e178837.png)

# Shark-Attack-Project
This project aimed exercise abilities of cleaning and manipulating data for data analysis.

## Objectives
The specific objective is to answer the following questions:
- What are the countries with more occurences of shark attacks?
- Which species are most deadly?

## Source of dataset
The dataset was downloaded from 'Global Shark Attacks' project in Kaggle website:
https://www.kaggle.com/datasets/teajay/global-shark-attacks

The dataset was compiled by a research group:
https://www.sharkattackfile.net/index.htm

The reports are registered by field investigators around the world and by population.

## Data cleaning premise
Aiming the most reliable data, it was disregarded:
- Registers before 1970;
- Countries with less than 100 registers.

## Technology
- Python 3.9.7

## Services Used
- GitHub

## Python Libraries
- Pandas
- Regex

## Data Analysis Outputs
### What are the countries with more occurences of shark attacks?
As seen in table 1, the country with more registers of shark attacks is USA, with 1588 attacks registered. Probabbly becouse is also the country with more field investigators. 
The following countries are Australia (566), South Africa (358) and Brazil (103), respectively.
According to the GSAF (Global Shark Attack Fiel) USA has 12 field investigators, Australia has 7, Africa has 2 and Brasil has 1.

##### Table 1 - Total registers per country and relative percentage of fatal/no fatal/ unknown cases
![image](https://user-images.githubusercontent.com/101889306/181916637-87ad5946-db16-4a2d-b701-18e184e05468.png)

The country with most fatal cases is Brazil. However, it is important to emphasize that Brazil has only one field investigator and has only 103 registered cases.
As seen in graph 1, from 1751 to 1872 the total registers corresponded of total fatal cases. The difference of total registers of fatal and no fatal/unknown increases throughout time. It make sense, becouse the more grave the case is, the more people needs help of other people for the treatment. There is not known why this difference increases throughout time, but one of the possibilities is  that the more research is fomented, the more registers of no fatal cases increases.

##### Graph 1 - Registered cases from 1751 to 1872
![image](https://user-images.githubusercontent.com/101889306/181917335-cee0daa2-2915-480e-8eb5-0271b5d6a7c6.png)

So, disregarding Brazil, the countries with the highest relative percentage of fatal cases are Australia and South Africa.

### Which species are most deadly?
According to Center for Surf Research (2022), the three most dangerous and aggressive species are: White shark, Bull shark and Tiger shark.
I cleanned theses species names from the dataset and recover the following subset (Table 2).

##### Table 2 - Relative percentage of fatal attacks by white, bull and tiger sharks and total attacks per country
![image](https://user-images.githubusercontent.com/101889306/181917807-12d25b34-0231-4979-9385-21b852be7785.png)

As seen in table 2, the most deadly shark is the bull shark, followed by white shark and tiger shark, respectively.

## Bibliography
Center of Surf Research. Most dangerous and aggressive sharks. 2022. 
Available in: https://centerforsurfresearch.org/most-dangerous-aggressive-sharks/

