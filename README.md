# DistributedWebCrawler

A Web Crawler with distributed functionality.

##Working:
1. Crawler.py does most of the heavy lifting. The Program starts with the link provided and starting from the root directory it crawls over all the pages.
2. Controller.py controls all the links that are being crawled.
  a. log.txt holds all the links that are crawled.
  b. dump.txt holds links that are dubplicated.
  c. Error.txt holds broken links.
