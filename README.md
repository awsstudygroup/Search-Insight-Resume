# Search Insight Resume

## Overview
Search Insight Resume is a web-based application designed to analyze and provide insights into resumes. It leverages advanced AI models, including Amazon Bedrock and the Anthropic Claude model, integrated with the LangChain library, to help users quickly understand the strengths and weaknesses of a resume. This tool is ideal for HR professionals and recruiters who want to streamline their resume screening process.

## Features
- Analyze resumes for specific skills and experience.
- Provide insights into areas such as AWS experience, backend development skills, and more.
- Easy-to-use interface for uploading and querying resumes.

## Setup
To get started with Search Insight Resume, follow these steps:

1. **Install Python**: Follow the instructions [here](https://docs.python-guide.org/starting/install3/linux/) to install Python.
2. **Set up a Python virtual environment**: Follow the guide [here](https://docs.python-guide.org/dev/virtualenvs/) to create and activate a virtual environment.
3. **Install AWS CLI**: Follow the quickstart guide [here](https://docs.aws.amazon.com/cli/latest/userguide/getting-started-quickstart.html) to install and configure the AWS CLI.

Clone the repository and install the required dependencies:
```bash
git clone https://github.com/awsstudygroup/Search-Insight-Resume
cd Search-Insight-Resume
pip3 install -r requirements.txt
streamlit run Home.py --server.port 8080
```

## Architecture
![Architecture](./Architecture.png)

## Usage
1. **Upload Resume**: Upload a PDF version of the resume you want to analyze.
2. **Ask Questions**: Type in specific questions you want to ask about the resume, such as "Does this resume have strong experience with AWS?"
3. **Get Insights**: Receive detailed insights and analysis based on the questions asked.

## Learn More About Prompt Design
- [Introduction to Prompt Design](https://docs.anthropic.com/claude/docs/introduction-to-prompt-design)

## Contributing
We welcome contributions to Search Insight Resume! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them with clear and descriptive messages.
4. Push your changes to your forked repository.
5. Open a pull request to the main repository.

## License
This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

## Contact
For any questions or feedback, please reach out to the project maintainers at [email@example.com](mailto:email@example.com).

