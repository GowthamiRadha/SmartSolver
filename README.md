Please note that the code for this project is hosted in a private repository.

# SmartSolver App

SmartSolver is a Streamlit web application that helps users solve real-time programming and statistical problems using ChatAPI's internal language model.

## Modules

The app has four modules:

### Main Module

This module allows users to upload files related to the programming or statistical problems along with question. If a file is uploaded, the app will extract basic information from the file to form prompts that are sent to ChatGPT along with the user's question. Users can also type in their questions in the provided text area and get immediate answers.

### Programming Module

The programming module has various options for common types of programming questions. Users can select the type of question they want to solve and provide the necessary inputs to get the correct answer. The inputs are used to form prompts that are sent to ChatGPT to provide the solution to the problem.

### TextToExcel Module

This module helps users solve statistical problems easily. Users can input the data in the text area, and upload an Excel sheet, and the app will extract basic information from the sheet to form prompts. ChatGPT will then provide the necessary statistical calculations based on the prompts.

## Dependencies

The application uses the following dependencies:

- Streamlit
- OpenAI's ChatAPI
- Pandas
- NumPy
- xlrd
- openpyxl

To install the dependencies, run the command `pip install -r requirements.txt`.

## Running the Application

To run the application, run the command `streamlit run Main.py` on the terminal. This will open the application in the browser, and users can interact with the different modules to solve their programming and statistical problems.

Once the application is running, users can select the desired module and follow the prompts to input their data or upload files. The app will extract basic information from the data or file and form prompts that are sent to ChatGPT to provide the answers to the problems.

Please note that SmartSolver requires an internet connection to use ChatAPI's language model.

## File Upload

The file upload feature currently supports only CSV and Excel file formats.
