# How to perform Pytest tests #
First install the requirements.txt file using the command: pip install -r requirements.txt

Then run the tests using the command: pytest

The tests can be found in the tests directory

# How to perform checks using OpenAPI #
Ensure the application is running by using the command: uvicorn app.main:app --host 0.0.0.0 --port 8000

Open a browser of your choice and navigate to http://localhost:8000/docs

The Swagger UI lists all available API endpoints along with their descriptions and input parameters. 

You can expand each endpoint to see more details and perform operations such as GET, POST, PUT, and DELETE.

Fill in the required fields and click execute button to send the request to the API endpoint. 
It should work as intended