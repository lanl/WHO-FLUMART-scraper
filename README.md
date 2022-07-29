# WHO FLUMART scraper

## AUTHOR
Geoffrey Fairchild
* [https://www.gfairchild.com/](https://www.gfairchild.com/)
* [https://github.com/gfairchild](https://github.com/gfairchild)
* [https://www.linkedin.com/in/gfairchild/](https://www.linkedin.com/in/gfairchild/)

## LICENSE
This software is licensed under the [BSD 3-Clause License](http://opensource.org/licenses/BSD-3-Clause). Please refer to the separate [LICENSE](LICENSE) file for the exact text of the license. You are obligated to give attribution if you use this code.

## ABOUT
This simple code can be used to collect global historical influenza surveillance data made public by the World Health Organization (WHO) on its [FLUMART](https://apps.who.int/flumart/Default?ReportNo=12) website purely through HTTP requests.

As it turns out, scraping this website is non-trivial due to the presence of several important hidden HTML values that are dynamically populated as the user interacts with the website. A separate open source scraping effort [here](https://github.com/mobinalhassan/WHO-Data-Downloader) relies on [Selenium](https://www.selenium.dev/), which can be finicky to setup and use, so I set out to scrape the data "properly" by interacting purely through HTTP requests.

Some of the key challenges to scraping this dataset were solved with the help of StackOverflow [here](https://stackoverflow.com/q/70009362).

## REQUIREMENTS
This code requires Python 3.6 or higher, [requests](https://github.com/requests/requests), and [Beautiful Soup 4](https://beautiful-soup-4.readthedocs.io/en/latest/).
