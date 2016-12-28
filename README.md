[![Code Climate](https://codeclimate.com/github/FreddieV4/VScraper/badges/gpa.svg)](https://codeclimate.com/github/FreddieV4/VScraper)

![alt tag](http://fjv4.com/img/portfolio/vscraper-banner.png)

A Python web scraping tool that allows users to scrape all files of the type they specify from URLs within the column of a CSV file and then download those files to their local directory.

# CSV Formatting
| Column 1            |
|---------------------|
| fjv4.com        |
| example.com    |
| website.com/folder/ |

# How to Run:
  1. Add URLs that you want to scrape from into a column of a CSV file (one URL per row)**
  
### In IDLE:

  * 2a. Run the program
  * 3a. Enter the name of the CSV file you created
  * 4a. Enter the type of file you want to scrape
  * 5a. Done! All of your files should have been scraped from the URLs, with an output displaying the number of files that were scraped
  
### On Linux/Mac OS:

  * 2b. Run `./VScraper.py csvname.csv code` from the command line
  * 3b. Done! All of your files should have been scraped from the URLs, with an output displaying the number of files that were scraped
  
  
### On Windows:

  * 2c. cd into the directory containing `VScraper.py`
  * 3c. Run `py VScraper.py csvname.csv code` in the command prompt
  * 4c. Done! All of your files should have been scraped from the URLs, with an output displaying the number of files that were scraped
  
**The arguments `csvname.csv` would be the name of your csv file, and `code` the type of file you want to scrape**

  
** **Make sure the CSV  file is in the same directory as VScraper.py**

## Requirements
  - This program was made and is run with Python 3.4.3 and uses these libraries in order to run:
  
      - [requests](http://docs.python-requests.org/en/latest/)
      - [BeautifulSoup4](http://www.crummy.com/software/BeautifulSoup/bs4/doc/)
      - [urllib](https://docs.python.org/3/library/urllib.html)
      - [csv](https://docs.python.org/3/library/csv.html)
      - [os](https://docs.python.org/3/library/os.html)
      - [sys](https://docs.python.org/2/library/sys.html)

## Problems/Suggestions?
Do either one of two things:
  1. Create an issue with your suggestion using the tag `enhancement`
  2. Fork this repository, make your changes to `VScraper.py` and submit a pull request

## License

Uses the [**MIT License**](https://github.com/FreddieV4/VScraper/blob/master/LICENSE)


-------
Want to find out more? Check out the [**Wiki**](https://www.github.com/FreddieV4/VScraper/wiki)
