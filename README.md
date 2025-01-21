# Importing flask module in the project is mandatory

# An object of Flask class is our WSGI application.

from flask import Flask

# Flask constructor takes the name of

# current module (**name**) as argument.

app = Flask(**name**)

# The route() function of the Flask class is a decorator,

# which tells the application which URL should call

# the associated function.

@app.route('/')

# ‘/’ URL is bound with hello_world() function.

def hello_world():
return 'Hello World'

# main driver function

if **name** == '**main**':

    # run() method of Flask class runs the application
    # on the local development server.
    app.run()
