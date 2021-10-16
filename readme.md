# CARTE Education Pathways
Name: Laith Hanania <br />
This repo is a clone of https://github.com/nelaturuk/education_pathways

## Activities 2 - 5
<img width="1680" alt="Part1" src="https://user-images.githubusercontent.com/50575615/137568655-1c89590c-c47c-41ef-9f60-be97a19675b3.png">
<img width="1680" alt="Part2" src="https://user-images.githubusercontent.com/50575615/137568660-40ed55b6-cc3d-4ed6-b4e9-2ab2f0119ead.png">
<img width="1675" alt="Part3" src="https://user-images.githubusercontent.com/50575615/137568663-b617a4fe-2567-4f1a-ad8a-cab70e7e4650.png">

## Activity 6
The major difference between the old UI and the new UI that is that the new UI has better separation between elements using borders. The old UI for the results page did not separate between the search and results well, giving the page a disorganized appearance. Furthermore, there were no visible separating columns in the table which made it more difficult to differentiate data points from each other. With the new UI, theres a clear separating between columns which improves the pages readability.

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
