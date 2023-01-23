# Scraping meta data from top articles on Medium from different topics using Beautiful Soup

Problem statement: Our task is to scrape important meta information pertaining to posts belonging to 5 different topics and export this information to an Excel sheet and a JSON file. The data we want is:

topic_name

topic_best_all_time_url

post_title

post_link

author_name

post_date 

read_time

author_follower_count 

post_clap_count

post_comment_count

post_tags 

A constraint is that I cannot use Selenium or any automation software.

So, the main idea is to create different lists for each of the above things, which can be then added to a dataframe as columns to make the final result.
The program will be then run through a list of all the topics to get the entire dataset and then imported as excel and json.
