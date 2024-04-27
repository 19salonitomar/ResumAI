# SmartATS Resume Matcher

SmartATS Resume Matcher is a Python-based application built with Streamlit and Google's Generative AI capabilities. It helps job seekers to tailor their resumes according to specific job descriptions by analyzing job postings and suggesting improvements to align resumes with the job requirements.

## Features

- **JD Analysis**: Automatically extracts key information from job descriptions using Google's Generative AI API.
- **Resume Matching**: Compares the content of the user's resume with the job description to identify matches and mismatches.
- **Recommendations**: Provides personalized recommendations on how to optimize the resume for better alignment with the job requirements.
- **Streamlit UI**: Offers an intuitive user interface powered by Streamlit for ease of use.

## Installation

To install and run SmartATS Resume Matcher locally, follow these steps:

1. Clone this repository to your local machine.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the application using `streamlit run app.py`.

## Usage

1. Launch the application by running `streamlit run app.py` in your terminal.
2. Upload your resume and the job description you want to match against.
3. The application will analyze both documents and provide you with insights and recommendations.

## Libraries Used

- [Streamlit](https://streamlit.io/): Used for building the user interface of the application.
- [Google Generative AI](https://github.com/google-research/sgan): Utilized for natural language processing tasks such as job description analysis.
- [PyPDF2](https://pythonhosted.org/PyPDF2/): Used for parsing PDF files, such as resumes.
- [python-dotenv](https://github.com/theskumar/python-dotenv): Used for loading environment variables.
- [json](https://docs.python.org/3/library/json.html): Used for handling JSON data.

## Contributing

Contributions are welcome! If you have any ideas for new features, bug fixes, or improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
