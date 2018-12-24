# twitter_crawler

This is a showcase of streaming tweets into a SQLite Database. You need to run two
seperate Rstudio Sessions, one for streaming the data into a json file in tmp (`stream.Rmd`) and a second that
picks those files up, parse, save to the DB, and clean the directory (`db.Rmd`). Of course you need your own 
twitter authentification (token). 
