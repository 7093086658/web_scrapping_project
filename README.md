

decription

This Python script extracts and processes product names and prices from a webpage using BeautifulSoup. It retrieves text data from a specified <div> element, cleans it, and structures it into two lists: one for names and another for prices.

Features

Parses HTML content using BeautifulSoup
Extracts text from a <div> with class 'main'
Cleans and processes the extracted text
Separates names and prices into respective lists

usage
Import the required libraries:

from bs4 import BeautifulSoup
import requests

Fetch the webpage content and parse it:

