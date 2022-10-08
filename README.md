# Example code for a Django and REACT.

This branch represents the project before any React stuff has been added.

## Setup instructions for the Frontend

```bash
# Enter frontend project folder
cd frontend
# install dependecies
npm install
# Compile code
npm run dev
# Then visit http://localhost:8000 (This started by the backend) to view change.
```

## Setup instructions for the Backend

```bash
# Enter backend project folder
cd backend
# Setup and activate virtualenv
virtualenv env
. env/bin/activate
# Install requirements
pip install -r requirements.txt
# Setup Django
./manage.py migrate
./manage.py runserver
# Then visit http://localhost:8000
```
