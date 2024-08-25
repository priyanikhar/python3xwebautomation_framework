

Tech Stack
Python 3.11
Requests - HTTP Requests
PyTest - Testing Framework
Reporting - Allure Report, PyTest HTML
Test Data - CSV, Excel, JSON
Parallel Execution - x distribute
How to Install Packages
pip install requests pytest pytest-html faker allure-pytest jsonschema 

To Freeze your Package version
ip freeze > requirements.txt 

To Install te Freeze Version
pip install -r requirements.txt 

How to run your Testcase Parallel
pip install pytest-xdist 

pytest -n auto tests/integration_test/test_create_booking.py -s -v  

To Work with the Excel
pip install openpyxl 

To work wit JSON Schema 

pip install jsonschema 

How to run via Jenkins(CI/CD)

Install all in one go
pip install allure-pytest selenium pytest openpyxl faker pytest-xdist pytest-html selenium