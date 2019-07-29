<img src="https://bit.ly/2VnXWr2" alt="Ironhack Logo" width="100"/>

# Most Popular Video Games 
*Paula Gual*

*Data Part Time Barcelona May 2019*

## Content
- [Project Description](#project)
- [Api](#api)
- [Website](#website)
- [Workflow](#workflow)
- [Results](#results)
- [Obstacles](#obstacles)
- [Lessons Learned](#lessons)

<a name="project"></a>

## Project Description
Scrapping the best 50 tops best bootcamps and also the funny phrases from Trump.
<a name="api"></a>

## API
The API is from the IGBD (Internet Games Data Base)
https://docs.tronalddump.io/

<a name="website"></a>

## Website
The websites are the websites of each game in the IGDB.

https://www.switchup.org/rankings/best-coding-bootcamps

## Workflow

### Find an API and a Website
* I tried first to use Twitter APIs, but due to limitation about the time range I preferred to use this API.
* For the website I tried to use something that can by also useful for us, for this reason I selected the switchUP

### API

* 1st I triedt to get a simple request
* Then I use a easy way to select each data that I want to use
* Put into a DF
* Clean and manipulate the data 

### WEB

* 1st I tried to web scrapte the whole info with a single command.
* 2nd creating query to retrieve the information that I want to gather.
* 3rd put into a DF 
* 4nd gatherind another information from a 2nd URL to complemente information about location
* Finally put everything into a DF

### Dataset

I export the dataframe in a csv on the output folder

<a name="results"></a>

## Results

A CSV with the 50 most popular games and its social links

<a name="obstacles"></a>

## Obstacles

Was hard to find a easy API to use.

<a name="lessons"></a>

## Lessons Learned

* Create a workflow is key to deliver a good result
* Is better to write the wholes steps while doing the analysis/manipulation
* Really awseome the fact that I was able to get further info in the webscrapping site.
