# Book-search-engine
To create a web application to search books using API from OpenLibrary using python. OpenLibrary offers suite of APIs to access Book related information. Use the API to build a simple Book search application.
VPT 2022 Qualifier Contest Project

We have developed a web application using Python Web Development Framework called 'Streamlit' that is popularly used for data analytics and ML purposes. Further details can be found here : https://streamlit.io/

This web application performs a HTTP Request to Open Libraries API to query for the search terms and returns the results. The search term could be book title or author name.

Prequisites :

OS - Platform Independent i.e. Linux or Windows

Python3

Pip3

Clone this repository with git clone command & run the following commands to prepare your environment :

Install Python3 from the following link (https://www.python.org/downloads/) or for linux python3 is present by default.

Install Pip - sudo apt install python3-pip, for windows this is present in python downloaded folder

Pip install -r requirements.txt

Python3 -m streamlit run app.py

Now the web app should be running in the localhost on port 8051 i.e., http://localhost:8501 visit this and search for your desired books.

This is also publicly hosted at : http://35.188.140.73:8501/

Future planned improvements :

Dockerize App

UI Development

Alternate enriched API adoption

Local DB for faster results

Application Features :

Search and return results - Book Title, Author, Book Cover

Exception Handling

Guidance :

The code has been commented for easier understanding

Requirements:

streamlit
IPython
