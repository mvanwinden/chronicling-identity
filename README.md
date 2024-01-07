# Kronieken in Kaart
### Geografische context en identiteitsvorming in kronieken na de Nederlandse Opstand (1568-1609)

## Usage
```bash
git clone https://github.com/mvanwinden/chronicling-identity
cd chronicling-identity
pip install -r requirements.txt
# run the Jupyter Notebooks in your favourite code editor
```

This repository contains 4 Jupyter Notebook collections that were used to collect geodata from 9 Dutch-language chronicles written between 1568 and 1609:
- **corpusstatistiek.ipynb** was used to gather information on a corpus of parsed chronicles (see 'Acknowledgements' below).
- **entity_linking.ipynb** uses data from GeoNames and the World Historical Gazetteer to entity link manually tagged locations in the chronicle to modern placenames.
- **geomatch_entities.ipynb** was used to create maps of the locations mentioned in the chronicles using Folium

The data used to execute these scripts is stored in the `data` folder. The output of these scripts is stored in the `output` folder. 

## Acknowledgements
- I have made use of the data that is available through the GeoNames database (https://www.geonames.org) and World Historical Gazetteer (https://whgazetteer.org/).
- The corpus of chronicles was created using an XML-parser developed by the Aarhus University Centre for Humanities Computing, which is available at https://github.com/centre-for-humanities-computing/dutch-chronicles.
- The chronicles originate from the Chronicling Novelty project that is ran by professor Judith Pollmann and doctor Erica Kuijpers (https://chronicling-novelty.com/).

```
@thesis{vanwinden_thesis_2023,
  location = {{Utrecht}},
  title = {Kronieken in Kaart. Geografische context en identiteitsvorming in kronieken na de Nederlandse Opstand (1568-1609)},
  institution = {{Utrecht University}},
  type = {Master's thesis},
  date = {2023},
  author = {Van Winden, Max}
}
```
