# Alan Du
This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1
![activity1](https://user-images.githubusercontent.com/39738139/137523424-6fee7886-40f1-434e-9a94-a28b43d99c9f.png)

## Activity 6
Comparing the old UI and the new UI, the most significant change is the readability of the search results table. Even though all the information is still the same, in the old UI, all the information was not formatted and shown with no padding between columns so it was hard to read. In the new UI, there is sufficient padding between table columns, there are lines for each cell and there is a clear header that tells the user what information they're looking at. Overall, this table is much easier to read and does a better job at conveying the information to the user.  

## Screenshots
### Home Page
![homepage](https://user-images.githubusercontent.com/39738139/137603085-97ab1509-eae9-4a67-8efd-7fc1dbcddb06.PNG)

### Results Page Form
![resultspage](https://user-images.githubusercontent.com/39738139/137603090-db7f2d9d-47d4-42d8-a0c4-cd4ed66bfeab.PNG)

### Results Page Table
![resultstable](https://user-images.githubusercontent.com/39738139/137603091-e3cb29a4-f1a1-46f9-8238-c862ded2a193.PNG)

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
