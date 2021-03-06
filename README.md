**Source:https://www.kaggle.com/gpreda/covid-world-vaccination-progress**

**Content:**


Country : This is the country for which the vaccination information is provided.

Country ISO Code - ISO code for the country.

Date - date for the data entry.

Total number of vaccinations - this is the absolute number of total immunizations in the country.

Total number of people vaccinated - a person, depending on the immunization scheme, will receive one or more (typically 2) vaccines; at a certain moment, the number of vaccination might be larger than the number of people;

Total number of people fully vaccinated - this is the number of people that received the entire set of immunization according to the immunization scheme (typically 2); at a certain moment in time, there might be a certain number of people that received one vaccine and another number (smaller) of people that received all vaccines in the scheme;

Daily vaccinations (raw) - for a certain data entry, the number of vaccination for that date/country;

Daily vaccinations - for a certain data entry, the number of vaccination for that date/country;

Total vaccinations per hundred - ratio (in percent) between vaccination number and total population up to the date in the country;

Total number of people vaccinated per hundred - ratio (in percent) between population immunized and total population up to the date in the country;

Total number of people fully vaccinated per hundred - ratio (in percent) between population fully immunized and total population up to the date in the country;

Number of vaccinations per day - number of daily vaccination for that day and country;

Daily vaccinations per million - ratio (in ppm) between vaccination number and total population for the current date in the country;

Vaccines used in the country - total number of vaccines used in the country (up to date);

Source name - source of the information (national authority, international organization, local organization etc.);

Source website - website of the source of information;


**Objectives:**

1. Which country is using what vaccine?
2. In which country the vaccination programme is more advanced?
3. Where are vaccinated more people per day? But in terms of percent from entire population ?

**EDA Procedure:**

1. Importing necessary libraries
2. Importing data set
3. Data preprocessing (removing the variables with large number of null values and renaming variables)
4. Analysis
5. Conclusion
