# CloudCoverAnalysis

Project for learning python and data science tools in way to make fun! The best way to learn new technology is to make interesting project with it.

## Astronomy and clouds

One of my hobby is astronomy and observation of night sky through binoculars or telescope. You can't observer sky if there is a lot of clouds there. I have strange filling that as time pass and climate slowly changes there are more and more cloudy nights over my house. On internet forum which garter all hobbyist in neighborhood this opinion is wieldy spread.

I thought that with current technology it should be an easy task to analyse trend in cloud cover over my area. I don't found any other project which was around this topic by searching in google for 5 minutes so I realize that this is perfect topic to learn more python and data science!

Main question to answer:

- Does cloud cover increase?
- Does number of nights with clear sky decrease?
- Does number of nights with clear sky vary much from place to place?
- What is best place to live (highest number of clear sky nights)?
- What is worst place to live (lowest number of clear sky nights)?

## Data source

I was surprise to find that getting access to data source was such easy task! I found that there is a lot of various very interesting data on EuMetSat. This agency is main source of meterological data for Europe. I found there product named cloud mask which describe cloud cover but there are a lot of other data about clouds. To get this data on your PC you need to register, accept rules, fill request for data and wait about 2 weeks until data will be available on internet to download.

## Notebook

As first stp please look on jupiter notebook which describe how load data, visualize it and do calculation.

## Usage

Short instruction:

1. Create virtual environment `virtualenv -p python3.6 venv`
1. Install packages `pip install -r requirements.txt`
1. And we need to fix one package `pip uninstall shapely`
1. Then  `pip install --no-binary :all: shapely`
1. Run Visual Studio Code and make fun!
