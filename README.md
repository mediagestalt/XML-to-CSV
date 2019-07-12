# XML to CSV

This is a quick bit of code to transform XML to CSV. This code was used to migrate an [InMagic database](https://lucidea.com/inmagic-dbtextworks/) to an [Atom database](https://www.accesstomemory.org/en/). The database has over 30,000 records

I know it's possible to read the XML and print to CSV (see [PeelXML](https://github.com/mediagestalt/PeelXML) for that, but this makes everything way faster and requires much less unnecessary cleaning. 

All of the code is described in the [Jupyter Notebook file](XML to CSV.ipynb).

## XML to JSON

The first step transforms the XML to JSON using the [xmltodict](https://pypi.org/project/xmltodict/) module. It really just reads the XML to json and saves it to a new file. 

## JSON to CSV

This code was entirely written by GitHub user [Vinay](https://github.com/vinay20045/json-to-csv). I didn't have to change this code at all. I did need to make a minor change to the json file, and that's described in the Jupyter notebook.
