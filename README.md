# Flask Session demo

A minimal Flask project that demonstrates session handling: set, read, and clear a text value using a web form.

Use the form on the main page to set a session value.
Use the links provided to clear the session value or view the session information.

## How to run

1. Install dependencies:
```
pip install -r requirements.txt
```
   or
```
py -m pip install -r requirements.txt
```
2. Start the server:
```
python app.py
```
   or
```
py app.py
```
3. Visit [http://127.0.0.1:5000/](http://127.0.0.1:5000/) in your browser.

## Routes

- `/`  
   Main page. Shows a form to set a text value in the session. Displays the current session value if set.

- `/clear`  
   Clears the text value from the session.

- `/session-info`  
   Shows all session data for the current user (as a dictionary).
