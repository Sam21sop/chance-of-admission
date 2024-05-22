# College Prediction

A Colleg Recommendation System For Engineering Admission.


## Motivation

Every year lakhs of junior college students pass their H.S.C and enter engineering colleges. While going through the admission procedure students need to enter some minimum count of colleges where they might have a chance to get admission. Because of this, a candidate needs to prepare a list of colleges to which he/she intends to get admission. This task of list generation requires a large amount of manual searching, comparing different prospects of colleges.

The goal of this project was to automate this college list generation. Aim was to reduce all this manual work by making a system that can effectively and efficiently generate a list of colleges in which a candidate is eligible based on the official database provided by the government. Recommendation systems solve the problem of "Information Overload" of searching through large volumes of data.


## Features

- Accepts both JEE and CET Marks
- Shortlisting colleges via Marks
- Shortlisting colleges via Engineering Branches
- Shortlisting colleges via Location/Distance
- Secured using SHA256
- Responsive web app
- Inclusive of other references



## Usage

This project can be used by:

- H.S.C pass-outs seeking admission in Engineering College......


## Tech Stack

 Python, Flask, SQLite3, Jinja, HTML, CSS, JQuery


## Run Locally

Clone the project

```bash
  git clone 
```

Go to the project directory after venv activation

```bash
  cd 
```

Install dependencies

```bash
  pip install requirements.txt
```

Local host the website

```bash
  python app.py
```


### Home Page
[!homepage](./static/homePage.JPG)

### Register Page
[!registeuser](./static/registerPage.JPG)

### Login Page
[!userLogin](./static/loginPage.JPG)

### Student Data and Branch Selection
[!branchselection](./static/branchSelectionPage.JPG)

### Predicted Result
[!result](./static/predictedColleges.JPG)