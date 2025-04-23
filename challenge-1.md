# Challenge #1

A 'simple' python Flask API application for retrieving Spotify song details.

## Disfunctional Requirements

| **Requirement** 	| **Description** 	|
|---:	|---	|
| **DFR1.** 	| The application needs to use Python 13.<br>https://www.python.org/ 	|
| **DFR2.** 	| The application needs to use Flask library.<br>https://flask.palletsprojects.com/en/stable/<br>`pip install flask` 	|
| **DFR3.** 	| All the python code should be typed.<br>eg. `def multiply(a: int, b: int): -> float` 	|
| **DFR4.** 	| All the data should be returned in JSON format. 	|
| **DFR5.** 	| The application needs to implement a CORS solution for backend-DFRontend communication. 	|
| **DFR6.** 	| The application should connect to the spotify API to do *cool stuff*.<br>https://developer.spotify.com/documentation/web-api 	|
| **DFR7.** 	| The application should return top 10/20/50 songs based on country or genere.<br>eg. `/api/top10?country=Ireland` or `/api/top50?genere=pop` or `/api/top-songs?lim=20&genere=rock` 	|
| **DFR8.** 	| The application can do any number of cool things with the Spotify api for no extra points. 	|

## Getting Started

### Downloading Python 13
You can get Python 13 from [python.org](https://www.python.org/) and install it to your system.

I recommend changing install location to a folder called `Python 13`, as you can download multiple versions of Python in the future and this will help you have them neatly organised.

### Setting up the environment
You can use VsCode or PyCharm or other Python IDEs for this.

I personally use VsCode.

You should always use a virtual environment with Python to keep your packages separate and not global. This is kind of like setting up `node_modules` folder in each project.
```sh
python -m venv venv
```

Once virtual environment is created, make sure you activate it when running your code/scripts. Your console should be pre-fixed with `(venv)` before it.

### Installing Flask
Inside of your virtual environment, run:
```sh
pip install flask
```
