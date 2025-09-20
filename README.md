Overview
Welcome to the Gemini Pro Applicant Tracking System (ATS)! This system is developed using the powerful Gemini Pro model to streamline the hiring process by analyzing job descriptions and resumes. It provides valuable insights such as job description match, missing keywords, and profile summary.

Demo of the project
 smart.ats.mp4 
Features
Job Description Match: The system evaluates how well a candidate's resume matches the provided job description, helping recruiters quickly identify suitable candidates.

Missing Keywords: It identifies keywords or skills that are missing in the resume but are crucial for the job, enabling recruiters to guide candidates on enhancing their profiles.

Profile Summary: The system generates a concise profile summary highlighting key strengths and qualifications, facilitating a quick understanding of the candidate's suitability for the position.

Requirements
Python 3.10
Gemini Pro model api key (Note: Ensure you have the necessary credentials and permissions to access the Gemini Pro API)
Installation
Clone the repository:
########   https://github.com/nitesh680/AI-RESUME-TRACKRE-for-job.git




Install dependencies:
pip install -r requirements.txt
Set up Gemini Pro API credentials:
Obtain API credentials from the makersuit platform.

Create a file named .env in the project root directory.

Add the following lines to .env:

GOOGLE_API_KEY= "your_api_key"


Usage
Run the application:
streamlit run app.py
Access the application through your web browser at http://localhost:5000.

Input the job description and candidate's resume in the provided fields.

Click the "Submit" button to initiate the analysis.

Review the results, including the job description match, missing keywords, and profile summary.

Contributing
If you would like to contribute to this project, please follow these steps:


Fork the repository.
Create a new branch for your feature or bug fix.
Make your changes and submit a pull request.


License
This project is licensed under the MIT License.





Contact
If you have any questions or issues, feel free to reach out to the maintainers:

Maintainer: Nitesh kumar
Email: niteshhx@gmail.com 

Happy recruiting with Gemini  ATS!
