# CV Parser

A tool to convert PDF resumes into structured JSON format using OpenAI's GPT-3.5-turbo.

## Features

- Extracts text from PDF resumes.
- Converts text to detailed JSON format.
- Uses environment variables for secure API key management.

## Requirements

- Python 3.9
- Conda
- OpenAI API key

## Installation

1. **Clone the Repository**
    ```sh
    git clone https://github.com/Ash-29/cv_parser.git
    cd cv_parser
    ```

2. **Create and Activate Conda Environment**
    ```sh
    conda create --name cv_parser_env python=3.9
    conda activate cv_parser_env
    ```

3. **Install Dependencies**
    ```sh
    pip install -r requirements.txt
    conda install ipykernel
    ```

4. **Add Environment to Jupyter**
    ```sh
    python -m ipykernel install --user --name=cv_parser_env --display-name "Python (cv_parser_env)"
    ```

5. **Set Up Environment Variables**
    - Create a `.env` file in the project directory:
      ```env
      OPENAI_API_KEY=your-api-key-here
      ```
    - Add `.env` to `.gitignore`:
      ```gitignore
      .env
      ```
