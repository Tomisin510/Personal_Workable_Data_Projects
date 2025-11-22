# Building a Python Web Scraping Project From Scratch

This project guide is a part of the [Zero to Data Analyst Bootcamp by Jovian](https://www.jovian.ai/data-analyst-bootcamp).

![](https://i.imgur.com/6zM7JBq.png)

Web scraping is the process of extracting and parsing data from websites in an automated fashion using a computer program. It's a useful technique for creating datasets for research and learning. Follow these steps to build a web scraping project from scratch using Python and its ecosystem of libraries:

1. **Pick a website and describe your objective**

    - Browse through different sites and pick on to scrape. Check the "Project Ideas" section for inspiration.
    - Identify the information you'd like to scrape from the site. Decide the format of the output CSV file.
    - Summarize your project idea and outline your strategy in a Juptyer notebook. Use the "New" button above.


2. **Use the requests library to download web pages**

    - Inspect the website's HTML source and identify the right URLs to download.
    - Download and save web pages locally using the `requests` library.
    - Create a function to automate downloading for different topics/search queries.


3. **Use Beautiful Soup to parse and extract information**

    - Parse and explore the structure of downloaded web pages using Beautiful soup.
    - Use the right properties and methods to extract the required information.
    - Create functions to extract from the page into lists and dictionaries.
    - (Optional) Use a REST API to acquire additional information if required.


4. **Create CSV file(s) with the extracted information**

    - Create functions for the end-to-end process of downloading, parsing, and saving CSVs.
    - Execute the function with different inputs to create a dataset of CSV files.
    - Verify the information in the CSV files by reading them back using [Pandas](https://pandas.pydata.org).


5. **Document and share your work**

    - Add proper headings and documentation in your Jupyter notebook.
    - Publish your Jupyter notebook to your [Jovian profile](https://jovian.ai/aakashns)
    - (Optional) Write a blog post about your project and share it online.


**Notes**

* Use the "New" button on [Jovian](https://jovian.ai) to create a new notebook, and select "Run on Binder" to get started.

* Follow this tutorial to learn web scraping: https://jovian.ai/aakashns/python-web-scraping-and-rest-api

* Check out 20-week bootcamp to learn Python programming, web scraping, data analysis and more: http://zerotoanalyst.com

Tweet your projects and tag [@JovianML](https://twitter.com/jovianml). We're retweeting 3 interesting proejcts everyday!
