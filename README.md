# CodeForces-Scraper
Selenium-Python based scraper for scraping the source codes and other information of the problems.

# Steps
1. Do conda install of selenium, beautifulsoup, json, and other packages in env.
2. Create a dir <Scraped Data> to contain all the scraped data in the same dir or at a lesser depth.
3. Run scraper after activating the env using --> python cofoScraper.py <Relative path of Dataset dir> <language-ID>.
4. Language-IDs:
  a. cpp.g++11
  b. cpp.g++14
  c. cpp.g++17
  d. c.gcc11
5. Let it run.
6. After completion, <Scraped Data> dir will be populated with a sub-dir, 'dataset' and a log file, 'logs.log' 
