# csv-automation

Exploring automation tasks with a simple csv.
Goals:


upload a .csv file with some data in it


have an automated (scheduled) unix-command-line job that archives a copy (with the then-current date appended to the filename) of that .csv file every ~1 hour to a folder on gitlab... so we have a version history of the .csv


have an automated (scheduled) job that runs a python script hourly... it would do some analysis based on loading what's in the .csv (into a pandas dataframe) and email those results... and also save those results to a new .csv file in the gitlab data folder


create an easy way to edit the .csv file (from a front-end similar to google-sheets or msft-excel)

