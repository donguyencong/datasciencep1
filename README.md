//Data Science Project 1

Messing up with CIA
Write a program that shall collect information about the total area, GDP (PPP), length of roadways, and length of railways in the world, per country, based on the CIA Worldfact Book (WFB).

https://www.cia.gov/Library/publications/the-world-factbook/print/textversion.html

The program shall start from the WFB main page (see URL above) and extract the URLs of all countries and territories, as well as their 2-letter codes. For each country and territory, the program shall download the fact page, from which extract the four parameters mentioned above. Each parameter shall be converted to a numeric value. If a parameter is missing (as it would be a case with any country without railways), the program shall set it to 0.

The program shall save the results into a CSV file called "cia.csv". The file shall have five columns: CountryCode, Area, GDP, Roads, Railways. The first row of the file shall have the column names. Each row of the file shall have a record pertaining to one country or territory.
