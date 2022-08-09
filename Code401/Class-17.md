# Web Scraping

[Home](../index.md)

## Web Scraping Basics

> Web scraping is a technique to automatically access and extract large amounts of information from a website, which can save a huge amount of time and effort.

This saves you from having to go to each website and click on every link and save it to your desktop.

### Permissions

It is important to note the permissions for use of data on a website. Most websites do not allow data to be used by third parties for commercial purposes. Also if you download data to quickly from a website this may crash the servers or get you blocked from the website.

### How to basics

Once you know the links of what you want to download. It's easy peasy! Use the following import statements.

```python
import requests
import urllib.request
import time
from bs4 import BeautifulSoup
```

Then using the `findAll` method you can get references to all the \<a\> tags on the website. Make sure to consider using `time.sleep()` to pause your code and not override the websites servers.

## Avoid being blocked while scraping

> 1. Make the crawling slower, do not slam the server, treat websites nicely
> 1. Do not follow the same crawling pattern
> 1. Make requests through Proxies and rotate them as needed
> 1. Rotate User Agents and corresponding HTTP Request Headers between requests
> 1. Use a headless browser like Puppeteer, Selenium or Playwright
> 1. Beware of Honey Pot Traps
> 1. Check if Website is Changing Layouts
> 1. Avoid scraping data behind a login
> 1. Use Captcha Solving Services

## What I Want to Know More About

Like always I am just curious to see this in action. But also I am curious to use this functionality along with Jupyter worksheets to gather and analyze large sets of data to get a competitive advantage in different marketplaces.
