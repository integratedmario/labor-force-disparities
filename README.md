---
output:
  pdf_document: default
  html_document: default
---
# Variable Descriptions

**Country**: A string corresponding to the name of a country.

**Continent**: A string corresponding to the continent the corresponding
  country is located in.
  
**LBFPRFem**: A double corresponding to the country's female labor force
  participation rate, in %.
  
**LBFPRMal**: A double corresponding to the country's male labor force
  participation rate, in %.
  
**LBFPRTotal**: A double corresponding to the country's total labor force
  participation rate, in %.
  
**LBFPRDiff**: A double corresponding to the disparity between female and
  male participation rates, with a positive value indicating a higher male
  value, in a percentage point difference.
  
**HDI**: The United Nation's Human Development Index, presented as a double
  and ranging from 0 to 1, and generally based on a country's quality of life,
  education, and gross national income per capita.
  
**GII**: The United Nation's Gender Inequality Index, presented as a double
  and ranging from 0 to 1, and generally based on equitable health,
  representation, and labor market participation.
  
**FSI**: The Fragile States Index, presented as a double from 0 to 100 and
  measuring a country's vulnerability to conflict and collapse, as a function
  of multiple other variables.
  
**SecondaryRatio**: The ratio of girls to boys in secondary school, presented
  as a positive double.
  
**TertiaryRatio**: The ratio of women to men in higher education, presented as
  a positive double, and containing NA values due to policies per country and
  lack of data reliability.
  
**WomenInGovt**: The representation of women in a country's legislature,
  presented as a %-based double.
  
**MaternalMortality**: The ratio of maternal deaths to live births multiplied
  by 100,000, and thus presented as a positive integer.
  
**Fertility**: The number of live births per women 15-49, presented as a
  positive double.
  
**TeenBirthRate**: The number of live births per 1,000 women aged 15-19,
  presented as a positive integer.

**EconomyFrag**: A positive double in a range from 0 to 10 indicating the
  general instability of a country's economy and corresponding system.
  
**EconIneq**: A positive double in a range from 0 to 10 indicating the scale
  of uneven economic development, inequitable hiring practices, and
  lack of equal opportunities.

**PublicServFrag**: A positive double in a range from 0 to 10 indicating
  the extent of lack of reasonable access to public services such as medicine,
  sanitation, potable water, and transportation/infrastructure.
  
**HumanRightsFrag**: A positive double in a range from 0 to 10 indicating
  the extent of lack of civil rights, protection of basic freedoms, openness
  of media and a fair justice system.
  
Note the crucial fact that for stability/fragility variables, higher values
indicate countries that are weaker/worse off. For general indices like HDI, 
lower values indicate more worse off countries.
