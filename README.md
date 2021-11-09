# Ebay webscraper

The python program `ebay_dl.py` was programmed to take an input of a search term through the python terminal and output either a json or csv file containing information on the name of the good, price of the good (in cents), how many items have been sold, the condition of the item, shipping costs (in cents) and the amount of the item sold.

To use the program use the following command in your terminal:
``` 
python3 ebay_dl.py "keyword" 
```
For example, if I am trying to find out the information on knives i would write:


``` 
python3 ebay_dl.py knife 
```

However, take notice, if you search query contains more than one word you should place quotes around the search term like this:


``` 
python3 ebay_dl.py 'dummy knife' 
```

**NB!** the default ouput file will be in a json format. If you wish to output a csv file you must add the argument `--csv` on the command line like this:

``` 
python3 ebay_dl.py 'dummy knife' --csv
```

Here is how I downloaded the json and csv files in my repository:

For the json file of flatscreen tv:

``` 
python3 ebay_dl.py 'flatscreen tv' 
```
For the csv file of flatscreen tv:
``` 
python3 ebay_dl.py 'flatscreen tv' --csv
```
For the json file of antique coffee table:
``` 
python3 ebay_dl.py 'antique coffee table' 
```
For the csv file of antique coffee table:
``` 
python3 ebay_dl.py 'antique coffee table' --csv
```
For the json file of mirror:
``` 
python3 ebay_dl.py mirror
```
For the csv file of mirror:
``` 
python3 ebay_dl.py mirror --csv 
```

Here is the [link](https://github.com/mikeizbicki/cmc-csci040/blob/2021fall/hw_03/README.md) to the course project

**Have fun playing around with this**
