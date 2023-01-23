### how to run the hello world flask app locally

Make sure you have Python installed on your computer. You can check this by running the command python --version in your command prompt or terminal.

Make sure that you have Flask installed in your system by running pip install flask in your command prompt or terminal.

Open a terminal or command prompt and navigate to the directory where your app.py file is located.

Run the command export 
```
FLASK_APP=app.py (on Linux or macOS) or set FLASK_APP=app.py (on Windows) 
```
to set the FLASK_APP environment variable to the name of your application file.

Run the command ```flask run``` to start the development server.

Once the development server is running, you can access your app by going to http://localhost:5000 in your web browser.

```
To check for syntax errors and print any error messages to the console use "python -m py_compile app.py"
```
