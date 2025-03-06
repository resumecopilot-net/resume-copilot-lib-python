# ResumeCopilot Python Library

## Overview
ResumeCopilotLib is a Python library designed to interact with the Resume Copilot API, allowing developers to integrate job search functionality into their applications.

## API Documentation
For detailed API documentation, visit:  
[Resume Copilot API](https://api.resumecopilot.net/swagger/index.html)

## What is Resume Copilot?
Resume Copilot is your one-stop solution for crafting the perfect resume. It is available as a plugin in the ChatGPT Plus version, helping users streamline their resume-building process. With Resume Copilot, you can:

- Effortlessly upload and edit resumes
- Make precise improvements and enhancements
- Choose from a diverse range of professional templates
- Navigate and implement suggested changes with ease

To learn more, visit:  
[Resume Copilot Website](https://resumecopilot.net/)

## ChatGPT Plugin
Resume Copilot is also available as a ChatGPT plugin to enhance your resume-writing experience. You can access it here:  
[Resume Copilot on ChatGPT](https://chatgpt.com/g/g-EcIzZRYVx-resume-copilot)

## Installation
To install the ResumeCopilot Python library via pip, use the following command:
```sh
pip install resume-copilot-lib
```

## Usage
Here's a basic example of how to use the library to perform a job search:
```python
from resume_copilot_lib import JobSearchHelper, JobSearchRequest

request = JobSearchRequest(
    title="developer",
    size=2
)

results = JobSearchHelper.search_jobs(request)
for job in results.jobs:
    print(f"Job: {job.name} at {job.company_name}")
```

## Contributing
We welcome contributions! Feel free to open issues or submit pull requests to improve the library.

## License
This project is licensed under the MIT License.