# Facebook-scraper

This is a scraper for Facebook that I adapted for an "ORCA" research project I was working on while an undergrad student at university. I didn't know how to use GitHub at the time, so I simply copied and pasted from the original GitHub repo. Credit to Max Woolf (minimaxir) from: 
  https://github.com/minimaxir/facebook-page-post-scraper/blob/master/examples/how_to_build_facebook_scraper.ipynb
  
This project was done from February - April 2018 to scrape posts from politicians whose pages were all public. Facebook has since updated their privacy policies and it is no longer possible to scrape statuses. Therefore, these text scrapers no longer work :( But when they did work, "orca_facebook_scraper.py" would scrape Facebook and create a csv file, organizing each post and its relevant information into their own rows. Then I would run "orca_fbpost_to_text.py" to take just the text from the posts/statuses and run through a separate application (AntConc) to do a linguistic analysis for things like word frequencies. The full write-up and data files have been excluded from this repo.
