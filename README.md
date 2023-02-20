# Scrapping_energy_data

Script downloads energy data from three sources:
1. https://www.pse.pl/dane-systemowe/funkcjonowanie-kse/raporty-dobowe-z-pracy-kse/generacja-mocy-jednostek-wytworczych
2. https://www.pse.pl/dane-systemowe/funkcjonowanie-kse/raporty-dobowe-z-pracy-kse/wielkosci-podstawowe 
3. https://tge.pl/energia-elektryczna-rdn

The script allows the user to choose date ranges for the first two sources, while for the third source, it retrieves current data that is embedded into the website.
Improvements for the future:
- Introducing the input() function to specify the date range
- Further web scraping for the tge.pl website. This website allows viewing data back up to three months
