# PaperCrawler
The PaperCrawler is for crawling papers of ACLAnthology.

This version supports crawling of titles, authors, links, and years of papers published in Top 4 NLP conference(ACL, EMNLP, CONLL, COLING).

If you wanna other attributes or conferences, please modify my code and make a pull request. Thank you!

## To install ChromeDriver

From [Chrome Web Driver](https://chromedriver.chromium.org/) link, Install the chromedriver appropriate for your operating system and the version of the Chrome web browser,

Save the chromedriver.exe(in the case of windows) file in the path of `/chromedriver`.

## Install libraries for crawling

* `pip install selenium`
* `pip install tqdm`
* `pip install pandas`
* `pip install openpyxl`

## Run
`python run_crawler.py --year CONFERENCE_YEAR --output_dir OUTPUT_DIR_PATH --chrome_driver_path CHROME_DRIVER_PATH`

