# ETLProj
A Python project template for ETL scripts and modules 


### Directory Structure ###

* bin
** Store your executable scripts here.
** agg.py, parse.py, and poll.py are example scripts as place holders for the different layers of ETL

* conf 
** configuration file

* core
** The meat and potatoes. 
** poll - Store you pollling modules here. Within this module you can have separate 
** parse - Parsing modules go here. These run once you have polled the data 
** agg - Second level aggregating modules go here for data sources that need to be normalized ahd have already been parsed separately. 

* docs
** Documentation goes here
** Recommend using Sphinx

* tests
** Testing scripts go here. Use them.
