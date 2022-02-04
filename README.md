## Scrapy Coding Challenge
Scrapy is an open-source framework for extracting data from websites. In order to do this
assignment, you would have to install scrapy from https://scrapy.org/ and you would need
python available on your machine.

Zyte has an offering called Scrapy Cloud, to deploy your spider in the cloud. You will be signing
up for a free account in Zyte Dashboard https://app.zyte.com/ and use the free unit of Scrapy
Cloud. No Credit card information is required. No other subscription is necessary for this task.

You will receive an email with an invitation to a Scrapy Cloud project for this purpose 
(if you do not, please let us know). [Instructions for deploying can be found here](https://support.zyte.com/support/solutions/articles/22000204081-deploying-your-spiders-to-scrapy-cloud)



### Assignment 1: Basic Spider and Deploy in Scrapy Cloud
The task is to build a spider to extract the following fields from all the 1000 books available in
the website: books.toscrape.com:
Fields to extract: book title, book price, book image URL, book details page URL
Constraints:
1. Your spider should visit all the categories pages and all the information should be
extracted from those.
2. Your spider should not visit the individual book pages. This way, you'll save a
considerable bandwidth.
3. Use of plugins and custom pipelines is optional. (bonus points)

Please provide the following two files in a github or bitbucket repo, and share the link:
a) Code of the spider
b) CSV or XML or JSON file of the four fields for the 1000 books
c) Link to the project deployed in Scrapy Cloud in Zyte Dashboard

### Assignment 2: Spider with Javascript
Scrape and extract quote, author and tags from http://quotes.toscrape.com/js/ You need to either use developer
tools to find out Ajax request and scrape content from API or use headless browser of choice. No need
to deploy this spider to Scrapy Cloud, just post extracted content here in repository.

Please provide the following two files in a github or bitbucket repo, and share the link:
a) Code of the spider
b) CSV or XML or JSON file with quotes data


### Deliverable ###

* The spider, committed and pushed to this repository

    The spider should be written in Python 3.8+ and follow the PEP8 style guidelines. Please also commit shub's `scrapinghub.yml` file (with any sensitive information removed).

    Please keep the followings points in mind when delivering your code:

    1. Commit History. Do not worry about delivering a clean commit history, do as many commits as you would do while working normally. Please do not squash everything into a single commit, we use the commit history to review the evolution of your work.
    2. Code quality. The final version of your code will be considered finished and production-ready - please make sure the spider results are complete and look correct upon inspection. You can check the [online documentation](https://doc.scrapy.org) to learn about Scrapy's features and best practices.
* Spent time report

    Please include a file called "hours.txt" with a list of tasks you worked on and the amounts of time you worked on them. You can be as detailed as you want, but a summary of high-level points is often enough (learning Scrapy, spider design, implementation, testing, etc). Keep in mind that this is not a time competition, a clean implementation is preferable over a quick one.

* Assumptions and decisions report

    Please document assumptions you made and reasons for decisions you made in a file called "assumptions.txt" in your repository. We will refer to this if your code contains things we did not expect.

* Feedback

    We would appreciate any feedback as per this trial. Please put it into "feedback.txt". Some specific questions are provided, but if you only have one thing to say, we're eager to receive any feedback at all. Please share!

### Time limit ###

We expect this project to take around 8-10 hours depending on your level of experience. We do not want you to over-invest yourself in this project, so if you're still working after spending 16 hours please stop and submit what you've completed.

### Deadlines ###

This project does not have a deadline. Just submit the results as soon as you have them ready (but no sooner) including the spent time report. The sooner you submit, the sooner we will move to the next step.

### Confidentiality ###

Please do not share code or specifications about this project with anyone outside Zyte.
