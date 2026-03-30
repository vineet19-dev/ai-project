# EVAL_SETUP Instructions

## Setup Instructions

1. **Clone the Repository**  
   To get started, clone the repository to your local machine:
   ```bash
   git clone https://github.com/vineet19-dev/ai-project.git
   cd ai-project
   ```

2. **Set Up Python Environment**  
   It's recommended to use a virtual environment. You can create one using the following commands:
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. **Install Dependencies**  
   Once the virtual environment is activated, install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

## Usage Instructions

1. **Running the Application**  
   After setting up your environment, you can run the main application with:
   ```bash
   python main.py
   ```

2. **Accessing the API**  
   If the application includes a web API, it is usually available at:
   ```bash
   http://localhost:5000/api
   ```

3. **Running Tests**  
   To ensure everything is working, you can run the test suite:
   ```bash
   pytest
   ```
   Make sure all tests pass before deploying.

## Additional Information

- For further details on configuration, refer to the documentation in the `/docs` folder.
- Make sure to check for any environment variables or additional settings necessary for deployment.