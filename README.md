# pdf-question-answer-bot
This is a Streamlit app that uses OpenAI's API to answer questions about PDF files.

# Description

This is a Streamlit app that uses OpenAI's API to answer questions about PDF files. The app allows users to upload a PDF file and ask any question they want. The app then extracts text from the PDF file using PyPDF2 or pdfminer, sends the question to the OpenAI API, and displays the answer to the user.

The app is designed to be easy to use and accessible to anyone who needs to extract information from PDF files. It can be used for a wide range of applications, from educational research to legal document analysis.

The repository includes all the necessary code and dependencies to run the app locally, as well as detailed instructions for setting up and running the app. It also includes sample PDF files and questions to help users get started.

# Features
* Upload PDF files to the app
* Ask any question related to the content of the PDF file
* Extract text from PDF files using PyPDF2 or pdfminer
* Use OpenAI's API to answer questions
* Display the answer to the user in the app
# Technologies used
* Python
* Streamlit
* OpenAI API
* PyPDF2 or pdfminer (for extracting text from PDF files)
* langchain

# Files

- `data/The Rise of Electric Vehicles.pdf`: A PDF file containing information about the rise of electric vehicles.
- `data/questions.txt`: A text file with example questions that can be asked about the content in the PDF.

# App Preview
Here are some GIFs showcasing the functionality of the app:
![GIF 1](./data/gif1.gif)
![GIF 2](./data/gif2.gif)
![GIF 3](./data/gif3.gif)

# How to Use
## Setting Up a Virtual Environment

To keep your project dependencies isolated, it's recommended to use a Python virtual environment. Here's how to set it up:


## To run the app, first clone the repository:
    git clone https://github.com/actuaryhafeez/pdf-question-answer-bot.git
## Create and Activate a Virtual Environment
On Windows:

    python -m venv venv
    venv\Scripts\activate

On macOS and Linux:

    python3 -m venv venv
    source venv/bin/activate

## Next, install the required packages using pip:
    pip install -r requirements.txt
    
## Then, run the app:
    streamlit run app.py

## Project Structure 

    pdf-question-answer-bot/
        ├── data/
        ├── app.py/
        ├── requirements.txt/
        ├── README.md/
        ├── .env-sample/
        ├── LICENSE/

        

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

This project adheres to the [Open Source Initiative's](https://opensource.org) definition of open source software and the [Open Source Initiative's Approved License List](https://opensource.org/licenses/alphabetical).

# Contributions
Contributions are welcome! If you find any issues or bugs, feel free to open an issue or submit a pull request.
