**Solar Rooftop Calculator**
This is a web application built with Flask that calculates the recommended capacity for rooftop solar panel installation, along with various financial and environmental metrics based on user inputs.

**Features**
Allows users to select their state and specify whether the property is residential.
Calculates the recommended kW capacity for rooftop solar installation based on average monthly bill, available roof area, required capacity, and other parameters.
Provides estimates for yearly energy production, financial savings, payback period, return on investment (ROI), and emission savings.
Input validation ensures that required fields are filled and appropriate values are entered.

**Getting Started**
Clone this repository to your local machine.
Install the required dependencies using pip install -r requirements.txt.
Run the Flask application by executing python app.py.
Access the application in your web browser at http://localhost:5000.

**Usage**
Select your state from the dropdown menu.
Check the "Residential Property" checkbox if applicable.
Enter the average monthly bill in rupees.
Enter the total available rooftop area and select the unit (square feet or square meters).
Specify the amount of investment, required capacity, and sanction load in kW.
Click on the "Calculate" button to see the results.
The results will be displayed below the form, showing the recommended kW for rooftop installation, yearly energy production, financial savings, payback period, ROI, and emission savings.

**Dependencies**
Flask: A micro web framework for Python.
Jinja2: A modern and designer-friendly templating engine for Python.
Pyngrok: A Python wrapper for ngrok, which provides secure introspectable tunnels to localhost.

**Contributing**
Contributions are welcome! If you find any bugs or have suggestions for improvement, please open an issue or submit a pull request.

**License**
