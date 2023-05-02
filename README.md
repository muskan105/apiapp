# Real Estate API

This is a RESTful API for a real estate application. It allows users to search for properties based on name, price, and ID.

# System Requirements

Python 3.6 or higher
Django 3.2.18 or higher
Django REST framework 3.12.4 or higher

# Installation Steps

# Clone the repository:
git clone https://github.com/username/realestate-api.git

# Navigate to the project directory:
cd realestate-api

# Install the required packages:
pip install -r requirements.txt

# Apply database migrations:
python manage.py migrate

# Start the server:
python manage.py runserver

#API Routes

# GET /realestate
Returns a list of all properties.

# GET /realestate/search
Searches for properties based on name, price, and ID. Supports the following query parameters:

DEMO- @http://127.0.0.1:8000/realestate/search=3 bhk
      @http://127.0.0.1:8000/realestate/search=1.45 cr

search: The search query.

# GET /realestate/{id}

DEMO- @http://127.0.0.1:8000/realestate/search/id=640ec38acebf274392fb7b02
Returns a single property with the specified ID.
