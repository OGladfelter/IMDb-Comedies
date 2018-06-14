# IMDb Comedies

Data comes from https://www.imdb.com/interfaces/ and from web scraping individual IMDb episode ratings pages

IMDb-webscraping-merging-munging.ipynb -- merging and subsetting downloaded IMDb datasets into a data frame of information about all episodes released by the top 100 comedies. Finished result includes a column which holds a list of the names of each writer on the observation's writing staff.

writer-gender-comp-calculate.ipynb -- use Gender API to predict gender of each unique writer, then calculate gender composition measures for each writing staff.
