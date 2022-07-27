# auth_wiki

It is a Webapp that has a library of authentication codes examples and community interactions.

## Technologies used and why?

* **Python** 

Python is extremely powerful, secure and very advanced for web design and development.
The Python library contains bundles of code that can be used repeatedly in different programs. It makes Python Programming simpler and convenient for the programmer. 

## Features
* `Sign-up`
        Enables users to register their details and gain access to the platform
* `Login`
       It is a security measure designed to prevent unauthorized access to confidential data
 * `Comment`
       Commenting or adding suggestions to a post in the form of text 
 * `Edit user details`
       User's credentials can be updated after signup. For example if the user wants to change their username, they can do so here
 * `List all users`
       To view all registered users
 * `Reactions`
        A user can react to an authentication code by giving it an thumbs-up or thumbs-down 
 * `Edit auth code`
        An Auth-Code is a code created by the webapp to help identify the domain name holder and it be edited using this feature.
* `Search Tab`
        It allows users to search for different authentication files in different languages
* `Download`
        Users can download code samples using the download button

## Requirements needed to be Registered

* Username
* Email
* Password 

When the credential is successfully verified during login, the request is authenticated

## Setup

### Prerequisites

The first thing to do is verify if Python and pip is installed in your system 

Execute python --version or python -V

![python version](https://www.howtogeek.com/wp-content/uploads/2022/04/3-python-version-powershell.png "python v")


Execute pip --version or pip -V

![pip version](https://miro.medium.com/max/700/1*7N3Trmjb1xt0uyaERNPbRA.png "pip v")

If it is not installed **[follow this guide](https://medium.com/co-learning-lounge/how-to-download-install-python-on-windows-2021-44a707994013#id_token=eyJhbGciOiJSUzI1NiIsImtpZCI6IjE1NDllMGFlZjU3NGQxYzdiZGQxMzZjMjAyYjhkMjkwNTgwYjE2NWMiLCJ0eXAiOiJKV1QifQ.eyJpc3MiOiJodHRwczovL2FjY291bnRzLmdvb2dsZS5jb20iLCJuYmYiOjE2NTg5NDY2NDUsImF1ZCI6IjIxNjI5NjAzNTgzNC1rMWs2cWUwNjBzMnRwMmEyamFtNGxqZGNtczAwc3R0Zy5hcHBzLmdvb2dsZXVzZXJjb250ZW50LmNvbSIsInN1YiI6IjExNTAxMDg3MzI3NDYxMjk2MTAwOCIsImVtYWlsIjoiYW5pYW1hcmE3MEBnbWFpbC5jb20iLCJlbWFpbF92ZXJpZmllZCI6dHJ1ZSwiYXpwIjoiMjE2Mjk2MDM1ODM0LWsxazZxZTA2MHMydHAyYTJqYW00bGpkY21zMDBzdHRnLmFwcHMuZ29vZ2xldXNlcmNvbnRlbnQuY29tIiwibmFtZSI6IkFtaWUiLCJwaWN0dXJlIjoiaHR0cHM6Ly9saDMuZ29vZ2xldXNlcmNvbnRlbnQuY29tL2EvQUl0YnZtbHhyWGlra25VMkZXMmFWLUhkc3oxQWo5M3ZZX041YXFqWnlCWXo9czk2LWMiLCJnaXZlbl9uYW1lIjoiQW1pZSIsImlhdCI6MTY1ODk0Njk0NSwiZXhwIjoxNjU4OTUwNTQ1LCJqdGkiOiJiZmRiMmNlNmYzODFmMjYwMjdkZDczMjVhODg2ZjQ4Y2Q1NDE4ZDU2In0.hwiLfSQLNFvMZLKp_UEUYXqkG7NkjllATvfwok6LYsJkVTB-dLum0ctW1N8mSjQ48e9X5HlYdGR6YCIbEeDe3WHgncyz-WleU2QuOCrHYCzyxem-KLHANRN8Cfia3Fl-j2qRrPPsfvC9XcZSam4ntTzfArhKegYndScci2g9niogqsUwe7yKYM8cg7P4OoSVAwgKNTWgdzV8WF_xQN82kS2Uj37S3A30-PuzhDQ2arejCWs7VZcVmh2dRF4XJ-02g8tXnVuQ-VpDC-Upt8vRqQuiL-fweNDXGX9DMr0RzJtgM4r5CQIfsbQxB38T8EUxBBQK3e9kACCkhoGO84LeBA)**



### Installation

##### Clone the repository and move to the folder

`git clone https://github.com/zuri-training/auth-wiki-team7.git`

`cd auth-wiki-team7`


##### To fetch for remote updates

`git fetch origin`


##### Pull latest changes from the main branch 

`git pull origin main`



### **NEXT:**

#####  Install and create a virtual environment package

`pip install virtualenv`

`python -m venv env`


##### Before you can start using packages in your virtual environment you'll need to activate it, so activate the virtual environment 

`env/scripts/activate`


##### Then install dependencies:

`pip install -r requirements.txt`


#####  Once pip has finished downloading the dependencies, migrate all models and make migrations

   `python manage.py migrate`


#####  Create admin account and Start Local Server
 
   `python manage.py createsuperuser`

   `python manage.py runserver`


Then open localhost:8000 on your browser to view the app



