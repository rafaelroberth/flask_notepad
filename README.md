# Website Project
================

A basic website built using Flask, a lightweight Python web framework.

## Features
------------

* Authentication routes:
	+ Login
	+ Logout
	+ Sign Up
* Home page
* Navigation bar with links to authenticated routes

## Requirements
---------------

* Python 3.x
* Flask 2.x
* Bootstrap 4.x
* Font Awesome 4.x

## Running the Project
------------------------

1. Clone this repository or download the project files.
2. Navigate to the project directory in your terminal/command prompt.
3. Install required dependencies using pip: `pip install flask bootstrap font-awesome`
4. Run the development server: `python main.py`
5. Access the website at `http://localhost:5000` in your web browser.

## Commit Message Guidelines
-----------------------------

* Use present tense (e.g., "Add new route" instead of "Added new route")
* Keep messages concise (<50 characters)

## Code Structure
------------------

The project is structured as follows:

```markdown
website/
main.py
__init__.py
auth.py
views.py
templates/
base.html
home.html
static/
index.js
requirements.txt
.gitignore
README.md