# SearchEngine-DFS

This is a SearchEngine Webapp project with DFS based web crawling.The project allows users to search for top 30 results according to their query and displays their search history.
The two main functions of the project are to perform a search and to get user search history.

TECH STACK

The project consists of three components: front end, back end, and a database.

HTML will be used for the front end, which is responsible for creating the structure of the web page.

CSS will be used for styling the web page, including elements such as background color, font color, and alignment.

JSP (Java Server Pages) will be used to connect the front end to the back end by allowing Java code to be written inside HTML files.

Java Servlets will be used for the back end, specifically for creating multiple mini servers to handle different types of calculations or operations.

MySQL, a popular database management system, will be used for storing and interacting with data

IDE- IntelliJ Idea

Project is Divided into two parts
1. SearchEngine- This takes users query and uses ranking algorithms to find 30 most relevant results from the database.
2. WebCrawler- Crawler is used to retrieve data from web pages.The crawler parses HTML pages and converts objects to Java objects.
   The retrieved data is provided to the indexer. The indexer saves the data to the database.
   Crawler bot uses DFS algorithm to navigate through the webpages.
