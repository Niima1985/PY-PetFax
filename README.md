# Activity: PetFax Introduction: 
We have been asked by a local animal shelter to create an application that shares fun animal facts alongside photos of the animals available for adoption. They hope this will be a fun way to get potential adoptees to engage with the shelter and find the animals loving new homes.

They just want us to create a proof of concept so let's use this opportunity and use a whole new stack to build the application. We will use Python and Flask, and later we will create our Postgres database for PetFax and then install and configure Flask-SQLAlchemy to connect to that database.

## Getting Started

1. Open your terminal.
2. Navigate to [PY-PetFax](./PetFax).
3. Open it in your code editor of choice.
4. Create the virtual environment if it does not exist.
   - `python3 -m venv venv`
5. Activate the virtual environment by running the command below for your operating system.
   - MacOS -> `. venv/bin/activate`
   - Windows -> `& .\venv\Scripts\Activate.ps1`
6. Run the app with `flask run --reload`.

**In terminal:**

1. With our virtual environment set up, we can now install the Flask package with pip.

```powershell
pip install Flask
```
## Installing Flask-SQLAlchemy

```powershell
pip install flask_sqlalchemy
```

1. Install the package through pip. Note that its package name is capitalized and hyphenated as `Flask-Migrate` during installation.
2. We also have to install a Postgres database adapter, `psycopg2-binary`.
   - This package will allow our Python application to work with Postgres.

```powershell
pip install Flask-Migrate
pip install psycopg2-binary
```

## Activity: Static Files and Styling and  Interacting with the PetFax Database
![GIF](screen-recording.gif)
