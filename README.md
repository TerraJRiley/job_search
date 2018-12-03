# Job Search
Applying data science skills to my job search to become a Data Scientist.

## Techie List
The list of techies was obtained earlier this year by doing some quick searches of lists of startups.  My original goal was to go through the list, add the url of the company's main website, a short discription of what they do and an initial impression of if their main function was something I had an interest in.  As I started working with Selenium I realized that I could write a basic script to search the name of the firm, select the link in description that seemed the most accurate and then automatically fill in both that information and my initial impression without needing to do all of the copy/pasting manually.  As such, I did that.

## Craigslist
Luckily the code written for the google search was eaily able to be used as an easy way to start searching craigslist.  As such, I ditched my attempt at using a craigslist wrapper that I found ineffecient and went purely with Selenium.  This time I will also be mimicking code I wrote for another selenium script that obtained data from each link in a list and the pages those links connected to.

### Success!
I've managed to obtain an initial scraping of the craigslist data and started to organize it in a pandas dataframe.

## Future Tasks
 - Clean the data.
 - Do EDA on the data.
 - Ensure I'm finding what I want to be looking for.
 - Try more search terms. (google "other terms for data scientist jobs" or something similar.)
 - Model for the jobs that we would actually be interested in.
    - Optomize such that we have more false positives than false negatives.

### Bonus Stuff:
- Unsupervised and then supervised modeling for different kinds of jobs.
 - Taylor our cover letter(s) & resume to each of those classes.
 - Put in code to respond to those jobs semi-automatically.
