This automation script is designed to perform various tasks related to flight tracking and scheduling on a web application. Below is a brief overview of the script files and their functionalities:

test.py

• This file contains a test function called test_RUN(driver) which orchestrates the automation process.
• The test function utilizes functions imported from src.modules and src.main modules to perform tasks such as tracking shipments, checking flight schedules, and validating error messages.
• Test data is provided in the data dictionary, including flight details like origin, destination, flight number, and date.
• The script provides instructions on installing required dependencies via pip and running the tests using pytest in the terminal.

main.py

• This file contains functions to perform specific actions related to flight tracking and scheduling.
• Functions like trackShipment(driver), flightSchedule(driver, origin, destination, flightNumber, date), and ErrorMessageValidation(driver, origin, destination) are defined to carry out tasks such as tracking shipments, checking flight schedules, and validating error messages.
• These functions utilize helper functions imported from src.modules and src.helpers modules to interact with the web application, locate elements, input values, wait for elements, and validate results.

Usage

1. Ensure that the required dependencies are installed by running pip install -r requirements.txt in the terminal.
2. Run the automation script using pytest by executing pytest -v -s in the terminal.

Note: This readme provides a high-level overview of the automation script. For detailed implementation and usage instructions, refer to the comments within the script files (test.py and main.py) and the corresponding modules (src/modules.py and src/helpers.py).