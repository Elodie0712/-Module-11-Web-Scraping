Scenario: You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
PART 1
1. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/a92d289a-b9ed-44a6-af36-ae4666d916e7)
2. Create a Beautiful Soup object and use it to extract text elements from the website.![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/4df8a6f7-b876-4fb4-8a42-a3cde8f31d4e)
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. ![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/3d673ee0-1d37-4ccb-aae0-f620f46b77c1)
PART 2
1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/5585d050-b650-4338-a8cd-d5cec226b6dc)
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/7d08b6c2-340d-4bfd-9596-774a20e7634d)
3. Assemble the scraped data into a Pandas DataFrame.![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/d8814374-a1ee-42e4-aa0d-6f3e4dfafd0e)
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/d61cb502-6bed-44ba-957c-e3e0623284e2)
5. Analyze your dataset by using Pandas functions to answer the following questions:
6.         a) How many months exist on Mars?![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/4dfff946-ad89-452a-8a0a-d39892bd2b91)
7.         b) How many Martian (and not Earth) days worth of data exist in the scraped dataset?![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/1a788a88-b2bc-4789-8b8d-d52498b62daa)
           c)  3. What is the average low temperature by month? 
![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/48dc2872-30cf-4707-be15-7b6bf1c116ea)
![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/2b111858-8f08-402a-9e93-542a719fc39a)
          d)Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.
![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/37e9e1ff-f1f3-46aa-9d55-dc4773716a76)
          e)About how many terrestrial (Earth) days exist in a Martian year?
          ![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/ce64e986-5d46-486d-a68c-d0e03962c8e8)


![image](https://github.com/Elodie0712/-Module-11-Web-Scraping/assets/148305373/260a45b8-402a-47ea-94a1-68705eef90c2)



