# giant_vegetables
Big vegetables are fun! And it's fall harvest season so why not.

Project description: Use BeautifulSoup to scrape weigh-off results for multiple years of giant vegetable competitions (pumpkins, tomatos, watermelons, long gourds, etc.)

Each category has it's own scrape notebook due to some minor differences in the source data tables. The 'gpc_scrape_testing' notebook is where I did the intial scrape testing to ensure I was connecting to the correct table and getting the desired output. Once that was running I made another notebook for each category that loops through the available years and consolidates all results into a dataframe that is written to csv for analysis.

Next step will be to visualize the data - platform TBD

Data gathered from Bigpumpkins.com: http://www.bigpumpkins.com/ViewArticle.asp?id=132