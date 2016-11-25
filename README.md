# uk-govt-cat-dashboard
A dashboard for the [UK government cat register](https://peterkwells.github.io/uk-government-cats/).

[View the dashboard](https://peterkwells.github.io/uk-govt-cat-dashboard/ukgovcats.html) which was created using the [bothan](https://bothan.io/) tool developed by the [ODI Labs team](https://theodi.org/labs).

Read a [blog](https://medium.com/@peterkwells/gov-cats-f143d4a7407b#.mx9junxy7) about how this was created.

Data comes from:

+ the unofficial [UK government cat register](https://peterkwells.github.io/uk-government-cats/)
+ the gov.uk [list of organisations](https://www.gov.uk/government/organisations)
+ data on the [cat population per postcode district](https://data.gov.uk/dataset/cat-population-per-postcode-district) produced by the [Animal and Plant Health Agency](https://www.gov.uk/government/organisations/animal-and-plant-health-agency)

The data is gathered from each of these sources, analysed and posted to Bothan via [Zapier](https://zapier.com). The dashboard will be updated whenever the cat register receives a new data commit or at the start of each month.

## Definitions

+ Schrödingers gov cats are entries in the register with status 'Inactive'
+ SW1 cats is the sum of entries in postcodes SW1[0-9]
+ Total gov cats is the number of entries in the register
+ Active gov cats is the number of cats in the register with status 'Active'
+ Total UK cats is the sum of all entries in the cat population data
+ Total UK governent departments is a manual sum of the data on gov.uk. Please suggest somewhere I can easily automate reading it :)


p.s. not got a gov cats earworm? [Listen](https://www.youtube.com/watch?v=mcUza_wWCfA).
