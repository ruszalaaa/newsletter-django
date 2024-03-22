# Newsletter Django App

This repository contains a Django application for a Newsletter App.

## Installation
1. Clone this repository to your local machine:
```bash
git clone https://github.com/szymonruszala5/newsletter-django.git
```
2. Navigate to the project directory:
```bash
cd news
```
3. It is recommended to set up a virtual environment before installing the project dependencies. You can use `venv` or `virtualenv` for this purpose. Assuming you have Python installed, you can create a virtual environment by running:
```bash
python -m venv env
```
4. Activate the virtual environment. On Windows, run:
```bash
.\env\Scripts\activate
```
On macOS and Linux, run:
```bash
source env/bin/activate
```
5. Install the required dependencies using pip:
```bash
pip install -r requirements.txt
```
## Configuration
1. Create a `.env` file in the root directory of the project and specify your configuration variables.
2. Make necessary database migrations:
```bash
python manage.py makemigrations
python manage.py migrate
```
## Running the Application
You can run the Django development server to start the application. Make sure your virtual environment is activated.
```bash
python manage.py runserver
```
The application will be accessible at `http://localhost:8000/`.
