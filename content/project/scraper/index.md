---
title: Scraping the Archive of German Far-right Weekly Junge Freiheit
summary: A webscraper in Python to collect text data from Germany's biggest weekly far-right newspaper.
tags:
date: '2020-11-01T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: 
  focal_point:


url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

This project came to fruition in fall 2020 in collaboration with {{< staticref "https://czymara.com/" "newtab" >}}Christian Czymara{{< /staticref >}}. The scraper lets you download articles by volume (all issues in one calendar year) from the archive of Germany's biggest far-right weekly by circulation, Junge Freiheit. The archive covers the time period from 1997 to the present, with new issues being uploaded with a several-week lag. 

The scraped data have individual articles as observations. Variables recorded for each article are date, title, the URL and the text. 

A more technical description of the project as well as the code for the scraper can be found {{< staticref "https://github.com/leo-bauer/junge-freiheit-scraper" "newtab" >}}here{{< /staticref >}}. Instructions and code on how to integrate the browser extension are written for Windows. Let me know if you would like the scraper to run on Linux. 
