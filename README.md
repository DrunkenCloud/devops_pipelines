# README.md

# Flask Minimal Application

This project is a minimal Flask application that demonstrates how to set up a simple web server with a single endpoint.

## Project Structure

```
flask-minimal
├── src
│   ├── app.py          # Main Flask application
│   └── test_app.py     # Tests for the Flask application
├── requirements.txt     # Project dependencies
└── README.md            # Project documentation
```

## Setup Instructions

1. Clone the repository:
   ```
   git clone <repository-url>
   cd flask-minimal
   ```

2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

3. Run the application:
   ```
   python src/app.py
   ```

4. Access the application in your web browser at `http://127.0.0.1:5000`.

## Usage

This application provides a single endpoint that can be accessed via a GET request. 

## Running Tests

To run the tests for the application, execute the following command:
```
python -m unittest src/test_app.py
```

## License

This project is licensed under the MIT License.