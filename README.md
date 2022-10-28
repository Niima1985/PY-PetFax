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

**What your terminal commands should look like:**

```powershell
pip install Flask
```
## Activity: Static Files and Styling
![GIF](static-files-and-styling-Activity.gif)

## Acceptance Criteria
- When running your app with `flask run --reload`, there should be no errors displayed on the browser.
- When visiting a `/pets/<index>` show page endpoint, the page should display a pet's name, image, and a fun fact.
- When visiting the `/facts/new` endpoint, the page should display a form for submitting a fun fact.