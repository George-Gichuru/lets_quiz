## Let's Quiz

This is an online programming quiz organizing website project, developed using Python's web framework Django.
For front-end designing I have used Twitter's front-end library Bootstrap4.

## Author Information

Written by George Gichuru.

## Installation

Clone the repository
Create a virtual environment
Install Django and other requirements in my requirements.txt file in your repository folder
Run the IP address on the browser

## Site access features

User must be logged in to access the Quiz.
For signup user is required to give username, first name, last name, e-mail address and password.
For login the user will be required to enter username and password only.

## Features of the quiz:

All questions are multiple choice question.
Each question is displayed only once per user.
Questions are displayed randomly for every user.
If the user by-mistake presses refresh or go back to the previous page, there will be a new question for the user and the question he/she was on will be marked as attempted.
A message will be displayed after every attempted question whether the answer was correct or incorrect.

## Leaderboard features:

Leaderboard is a shorted list according to the score obtained by the users.
If two users are having same score, the user who has signed up earlier will have good ranking than the one who joined late.
Leaderboard is open to all. No login required.

## Administrative features:

Only admin can add questions.
Admin can add questions and modify them until they are not marked as Has been published?
Once a question has been published, it can neither be modified nor can be accessed. Admin can only see a list of questions.
Admin can search questions by question text or choice text.
Admin can filter questions based on whether the questions have been published or not.

## SetUp / Installation Requirements

### Prerequisites

- python3.10.4
- pip
- virtualenv

## Running the Application

- Creating the virtual environment

        $ python3.10.4 -m venv --without-pip env
        $ source env/bin/activate

- Installing Django

        $ python3.10.4 -m pip install Django
        $ python3.10.4 -m pip install djangorestframework
        $ python3.10.4 -m pip install psycopg2

## Technologies Used

- Python3.10.4
- Django
- Bootstrap
- Javascript

Live Link: >

## Contact Information

To reach me, email me at: > gichurugeorge092@gmail.com

License
MIT License

Copyright (c) [2022] [**GEORGE-GICHURU**]

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
