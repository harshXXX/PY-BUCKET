# PY-BUCKET
This web app provide AWS S3 based file managing features including UPLOAD, DELETE, DOWNLOAD along with login features.
(https://i.ibb.co/myrY9Zb/output-onlinepngtools.png)

### Project Overview
> To Develop an application that provides a list of items in a AWS S3 bucket as well as provide a user registration and authentication system. Registered users will have the ability to UPLOAD, DOWLOAD and DELETE their own items in the BUCKET.

### Why This Project?
> Modern web applications perform a variety of functions and provide amazing features and utilities to their users; but deep down, it’s really all just creating, reading, updating and deleting data. In this project, I combined my knowledge of building dynamic websites with persistent data storage to create a web application that provides a compelling service to your users.

### What Did I Learn?
  * Develop a RESTful web application using the Python framework Flask
  * Implementing Flask-login and Flask-jwt-extended for security.
  * Implementing UPLOAD, DOWLOAD and DELETE in a S3 bucket.
  * Throttling for API call rate
  * Responsive UI
  
### How to Run?

#### PreRequisites
  * [Python ~3.7](https://www.python.org/)
  
#### Setup Project:
  1. Clone or Download the project and `cd` into the `PyBucket/` folder.

  2. Upgrade PIP
   `$ python3 -m pip install --user --upgrade pip`

  3. Installing venv
  - On macOS and Linux:
  `$ python3 -m pip install --user virtualenv`

  -On Windows:
  `py -m pip install --user virtualenv`

  4. Commands to activate virtual:

  - On macOS and Linux:
  `$ source env/bin/activate`

  - On Windows:
  `.\env\Scripts\activate`

  5. Install dependencies:
  `$ pip install -r requirements.txt`

  6. Change AWS *S3_KEY*, *S3_SECRET* and *S3_BUCKET* with your own values in `.env` file.
  ```
  source env/bin/actvate
  export FLASK_APP=app.py
  export FLASK_DEBUG=1

  export S3_BUCKET='pybucket' #dummy
  export S3_KEY='AKIAIUC2W6JYXMZA' #dummy
  export S3_SECRET='2GIY6m6OxPgwSJzogrACbXjfi9k' #dummy
  ```

#### Launch Project
  1. run the app using command:
  `$ flask run`
  
  2. Access and test your application by visiting [http://localhost:5000](http://localhost:5000).


### If you're running into issues:
contact me on [twitter](https://www.twitter.com/harshsahu97/)