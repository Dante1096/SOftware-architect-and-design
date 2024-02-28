# Django Hello World App

This is a simple Django app that demonstrates how to create a Hello World message and serve it as both JSON and HTML responses.

## Prerequisites

- Python 3.x
- Django

## Installation

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:

    ```bash
    cd helloworld_project
    ```

3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Launching the App

To launch the Django app and access the Hello World messages:

1. Start the Django development server:

    ```bash
    python manage.py runserver
    ```

2. Access the HTML response:

    Open a web browser and go to: [http://127.0.0.1:8000/hello/](http://127.0.0.1:8000/hello/)

    You should see a page with the message "Hello World!" displayed in bold.

3. Access the JSON response:

    Open a web browser and go to: [http://127.0.0.1:8000/hello/json/](http://127.0.0.1:8000/hello/json/)

    You should see a JSON response: `{"Message": "Hello World!"}`

