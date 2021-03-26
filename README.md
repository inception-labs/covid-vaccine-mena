# Covid Vaccination Data for MENA Region
All dates are coded according to ISO 86O1 (YYYY-MM-DD) format. All countries are represented by their [ISO 3116 three-character code](https://unstats.un.org/unsd/tradekb/knowledgebase/country-code).

## Demographics Files
- **MENAR-Countries.csv:** The population estimates we use to calculate per-capita metrics are based upon the last revision of the [World Bank Population Prospects](https://data.worldbank.org/indicator/SP.POP.TOTL) (2019). The values used can be viewed in [MENAR-Countries.csv](https://github.com/inception-labs/covid-vaccine-mena/blob/main/MENAR-Countries.csv).
- **MENAR-CountriesCOVID.csv:** Data on COVID Total-deaths, smoothed-deaths, Total-cases, and smoothed-cases are gathered from [Our World in Data's COVID-19 dataset](https://github.com/owid/covid-19-data/blob/master/public/data/README.md)

## Donations Files
- **COVAX-Eligibility.csv:** Countries that are COVAX AMC-Eligible have been outlined by [Gavi's 2020-12-15 publication.](https://www.gavi.org/sites/default/files/covid/pr/COVAX_CA_COIP_List_COVAX_PR_15-12.pdf)
- **COVAX-DonationHistory.csv:** Countries that have pledged donations to COVAX AMC have been outlined by [GAVI.](https://www.gavi.org/sites/default/files/covid/covax/COVAX-AMC-Donors-Table.pdf)

## Vaccines Files
- **Vaccine-Agreements.csv:** Vaccine agreement in each country are reported based on public official sources.
- - **Vaccines-Authorized.csv:** Vaccine authorizations in each county are reported based on public official sources. Sources are posted along with the date of authorization for each respective country.

## Distribution Files
- **Vaccine-Accessibility.csv:** Data on the registration platform used in each country (online vs. SMS text vs. Electronic health messages) as well as the URL sources for online registration websites.
- **Vaccine-Eligibility.csv:** Data tracking which subpopulations are eligible for vaccination throughout vaccine rollout.
- **Vaccine-Progress.csv:** The number of vaccine doses delivered in each country are drawn from official governmental websites and public offcial statements. Official sources for each country and date can be round in the data repository. Since most available vaccines require two doses, We are reporting two types of vaccine data. The number of people who received at least one vaccine dose are represented by the One-Dose metric, and the number of people who received two vaccine doses are represented in the Total-Vaccinated metric. 

## Citations
- Our World in Data: Hasell, J., Mathieu, E., Beltekian, D. et al. A cross-country database of COVID-19 testing. Sci Data 7, 345 (2020). https://doi.org/10.1038/s41597-020-00688-8
