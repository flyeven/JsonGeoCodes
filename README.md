JsonGeoCodes
============

JSON data of nations, districts and other geo informations.


Countries.json
==============
Contains all world's nations name and relative international code

Example:

```
    {
        "Name": "Afghanistan",
        "Code": "AF"
    }
```
	
	
Regions.json
==============
Contains all regions of any world nation, including relative country name and country code.

Example:

```
  {
    "CountryName": "Andorra",
    "CountryCode": "AD",
    "Regions":
	[
      "Andorra la Vella",
      "Canillo",
      "Encamp",
      "Escaldes-Engordany",
      "La Massana",
      "Ordino",
      "Sant Julia de Loria"
    ]
  }
```
  
Districts.json
==============
Contains districts of all regions of any world nation, including relative region name, country name and country code.

Example:
```
  {
    "CountryName": "Italy",
    "CountryCode": "IT",
    "Region": "Liguria",
    "Districts": [
      "Provincia di Savona",
      "Provincia di La Spezia",
      "Provincia di Imperia",
      "Provincia di Genova"
    ]
  }
```