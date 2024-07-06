# ATS Resume Expert

## Description
ATS Resume Expert is a Streamlit web application designed to evaluate resumes against job descriptions using advanced AI capabilities. This tool allows users to upload a resume in PDF format and input a job description. The application then analyzes the resume for compatibility with the job description using natural language processing (NLP) techniques and AI models.

## Key Features
- **Resume Analysis:** Upload your resume in PDF format and receive a detailed analysis of how well it matches the provided job description.
- **AI-Powered Evaluation:** Utilizes Google's generative AI API to generate responses that highlight strengths, weaknesses, and overall alignment.
- **Percentage Match:** Get a percentage match score indicating how well the resume fits the job description.
- **Keyword Identification:** Identify missing keywords that are crucial for the job application.

## Key Skills
- **Python (Streamlit framework):** For building the web application interface.
- **PDF Processing (pdf2image, PIL):** For handling and converting PDF files.
- **Natural Language Processing (NLP):** For analyzing the job description and resume content.
- **AI and Machine Learning:** Using Google's generative AI API for content generation and evaluation.
- **File Handling and Manipulation (io, base64):** For processing and encoding files.
- **Front-end Development (Streamlit widgets):** For creating interactive user interfaces.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/omghumre/ats-resume-expert.git
    cd ats-resume-expert
    ```

2. Create and activate a virtual environment:
    ```bash
    python -m venv env
    source env/bin/activate  # On Windows use `env\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the environment variables:
    Create a `.env` file in the root directory and add your Google API key:
    ```
    GOOGLE_API_KEY=your_api_key_here
    ```

## Usage

1. Run the Streamlit app:
    ```bash
    streamlit run app.py
    ```

2. Open your web browser and go to `http://localhost:8501`.

3. Follow the on-screen instructions:
    - Enter the job description in the provided text area.
    - Upload your resume in PDF format.
    - Click on "Tell Me About the Resume" to get a detailed evaluation or "Percentage match" to get a match score and keyword analysis.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.

---

Feel free to customize this README as per your project's requirements.
