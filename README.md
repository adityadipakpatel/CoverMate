# CoverMate

**CoverMate** is a simple tool to help you automate the process of generating personalized cover letters. By providing your resume content and job application details in plain text files, the program will generate a customized ChatGPT prompt or LaTeX-ready cover letter.

## Features
- Input your resume content and job application details in `resume.txt` and `job_application_content.txt`.
- The script generates a ChatGPT prompt for quick use or a LaTeX cover letter based on a pre-defined template (`cover_letter_template.tex`).
- Easy-to-use with no need for advanced configuration.

## Installation

1. Clone the repository:
    ```bash
    git clone git@github.com:adityadipakpatel/CoverMate.git
    cd CoverMate
    ```

2. Install required dependencies (if any):
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Prepare your files:**
    - Put your resume content in `resume.txt`.
    - Put the job application requirements in `job_application_content.txt`.

2. **Run the script:**
    ```bash
    python generate_cover_letter.py
    ```

3. The script will:
    - Read your resume and job application content.
    - Generate a customized ChatGPT prompt for you to paste directly into ChatGPT for generating a cover letter.
    - Alternatively, the script will use the `cover_letter_template.tex` to generate a LaTeX cover letter.


## Contributing

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature-name`).
3. Commit your changes (`git commit -m 'Add feature'`).
4. Push to the branch (`git push origin feature-name`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
