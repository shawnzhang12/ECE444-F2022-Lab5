This repo is a clone of 
https://github.com/nelaturuk/education_pathways. 
Lab 5 done by Xiao En (Shawn) Zhang, Boyuan (Jesse) Shao, and Nicola Lawford.

**Activity 1**

![](images/activity1.png)

**Activities 2-5**

Results Page – Form
![](images/activity2-5_home.png)

Results Page – Results Table
![](images/activity2-5_results.png)

**Activity 6**

User Story 3.1.1

![](images/userstory311.png)

![](images/userstory311-frontend.png)

User Story 3.2.1

<img width="708" alt="Screenshot 2022-10-26 at 9 53 23 PM" src="https://user-images.githubusercontent.com/59927679/198172662-685ceaa9-7b5d-41eb-b7d0-fecf9b520fd5.png">

![IMG_1637](https://user-images.githubusercontent.com/59927679/198172697-2076c213-c062-41ed-afe2-e1433a5151cf.jpg)

User Story 3.4.2
![](images/userstory342.png)

![](images/career_explorer_user_story.png)
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
