# Kneescrape
> Build a targeted dictionary and gather email adresses from any website

A simple infosec tool for crawling a website and scrape for email addresses and unique and 
relevant words to build a targeted dictionary.

## Installing / Getting started

If you have downloaded the tar.gz package or cloned this repository, you can install
using the setup.py script.
```shell
sudo python setup.py install
```

The project is submitted to pypi so the easiest way of installation is using pip.
```shell
sudo pip install kneescrape
```

Give it a go!
```shell
kneescrape www.microsoft.com microsoft
```
This will start scraping www.microsoft.com and save the findings in ./microsoft folder.

### Initial Configuration

You may need to install lxml. Kneescrape will tell if you this is the case.

```shell
sudo pip install lxml
```
