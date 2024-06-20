# Using Playwright to scrape state-level license and violations data

## IRE 2024, Los Angeles

Jonathan Soma, Knight Chair in Data Journalism at Columbia Journalism School

**Contact:** [jonathan.soma@gmail.com](mailto:jonathan.soma@gmail.com) / [@dangerscarf](https://twitter.com/dangerscarf) / [jonathansoma.com](https://jonathansoma.com/)

## What is this?

State-level agencies always have *absolutely awful* websites for accessing information. It's horrible, it's awful, it's tragic, and it's a total pain to try to kidnap the data through scraping.

In these examples we're going to try to scrape a wide, wide, wide selection of different sites, using common approaches you can *hopefully* adapt to your own "this site has data I want!" situations. For most of these you don't need to know anything except how to hold down shift and press enter.

Each example uses [Playwright](https://playwright.dev/python/) for scraping, a "browser automation tool" that controls a browser for you. This allows you to click, use dropdowns, all sorts of fun stuff. It's *also* very fulfilling because once you run the code it's like a secret computer ghost is controlling your browser (and doing all of your work for you).

It's *also also* great because unlike traditional scraping you can actually see what's going on with the page, which makes things a little more... accessible? friendly?

## The examples

- [Texas Tow Trucks Licenses](01-Texas%20Tow%20Trucks%20Licenses.ipynb): dropdowns
- [Iowa Appraisal Management Companies](02-Iowa%20Appraisal%20Management%20Companies.ipynb): dropdowns, 'next page' buttons
- [New Jersey Perfusionists](03-New%20Jersey%20Perfusionists.ipynb): dropdowns, numbered pages
- [Massachusetts Optometrists](04-Massachusetts%20Optometrists.ipynb): dropdowns, downloading files
- [North Dakota Oil Wells](05-North%20Dakota%20Oil%20Wells.ipynb): dropdowns, using every dropdown option
- [Maryland Locksmiths](06-Maryland%20Locksmiths.ipynb): 
- [California Midwives](07-California%20Midwives.ipynb): 
- [Texas Tow Trucks Details](08-Texas%20Tow%20Trucks%20Details.ipynb): 
- [Chicago Buildings](09-Chicago%20Buildings.ipynb): 
- [Texas Medical Board Actions](10-Texas%20Medical%20Board%20Actions.ipynb): 
- [Texas Medical Board Actions Details](11-Texas%20Medical%20Board%20Actions%20Details.ipynb): 
- [Ohio, a failure](12-Ohio.ipynb): 

## More links

If you'd like a general-purpose introduction to Playwright [try this one](https://jsoma.github.io/advanced-scraping-with-playwright/), and if you want to know how to break CAPTCHAs, [here you go](https://jonathansoma.com/everything/scraping/solving-captchas-in-playwright-with-nopecha/)!

The [Playwright documentation](https://playwright.dev/python/) is also pretty good.

And completely unrelated but *very* popular is my [Practical AI for Investigative Journalism](https://www.youtube.com/playlist?list=PLewNEVDy7gq1_GPUaL0OQ31QsiHP5ncAQ).