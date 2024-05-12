# Flower Classifier Web App

This is a simple web application built with Flask that uses a machine learning model to classify flowers based on their sepal and petal dimensions.

## Getting Started

To run this application locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python packages using pip:
    `pip install -r requirements.txt`
3. Ensure you have a trained machine learning model saved as `saved_model.sav`.
4. Run the Flask application:`python app.py`
5. Open your web browser and navigate to [http://localhost:5000](http://localhost:5000) to access the application.

## Usage

Once the application is running, you can input the sepal and petal dimensions of a flower into the form fields and click the "Predict" button. The application will then display the predicted class of the flower based on the trained machine learning model.

## Dependencies

- Flask: Web framework for Python
- scikit-learn: Machine learning library for Python

## File Structure

- `app.py`: Main Flask application file containing route definitions.
- `templates/index.html`: HTML template for the web interface.
- `saved_model.sav`: Pickled machine learning model for flower classification.
- `requirements.txt`: List of Python dependencies.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE) file for details.
       
