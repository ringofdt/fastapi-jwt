# Securing FastAPI with JWT Token-based Authentication

### Want to learn how to build this?

Check out the [post](https://testdriven.io/blog/fastapi-jwt-auth/).

## Want to use this project?

1. Fork/Clone

1. Create and activate a virtual environment:

    ```sh
    $ python3 -m venv venv && source venv/bin/activate
    ```

1. Install the requirements:

    ```sh
    (venv)$ pip install -r requirements.txt
    ```

1. set ENV:

    ```sh
    # setup .env
    touch .env
    echo "secret=secret-shhh" >> .env
    echo "algorithm=HS256" >> .env
    ```

1. Run the app:

    ```sh
    (venv)$ python main.py
    ```

1. Test at [http://localhost:5051/docs](http://localhost:5051/docs)
