# pythonwebapp

Developed a Web applicationn using Python's webapp2 framework which is compatible with Google App Engine webapp. The users can signup,
signin and logout along with posting blogs and reading blogs from other users.

Google App Engine's datastore is used as a database for storing the blogs submitted by the users.
To reduce the number of queries made to the datastore, top 10 blogs are being cached.

Requirements:
  Python 2.7
  Google App engine
  
Libraries Used:
  Jinja Library for templates
  
