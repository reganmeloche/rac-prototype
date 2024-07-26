# Rules-as-Code Proof of Concept

This application demonstrates how Rules-as-Code can be leveraged to facilitate Access to information requests.

...

## Setup

The application can be run using manual commands or using Docker

First, set up a virtual environment:

```
python -m venv venv
. venv/Scripts/activate 
```

To run it using manual commands, first install the dependencies:

```
pip install -r requirements.txt
```

Run the Flask application:
```
python app.py
```

If using Docker, then simply run `docker-compose up`.

Navigate to `localhost:5000` to access the app.
