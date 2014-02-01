# Albuquerque, NM crime data
Albuquerque crime data from the Albuquerque Police Dept. via [CrimeMapping.com](http://www.crimemapping.com/).

The data was scraped from the HTML "Detailed Report" and converted to JSON using the (2 minute) script crimeparse.py. The format has only been tested in the most rudimentary way.

The current Albuquerque crime data covers the dates 5 Aug 2013 - 31 Jan 2014.

### Metadata
Current fields are:
* 'agency'
* 'date'
* 'location'
* 'description'
* 'case_number'
