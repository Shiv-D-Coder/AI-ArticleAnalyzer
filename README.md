
![Crew AI Logo](https://www.crewai.com/assets/crew_only-ce3e8e1afde0977caeaa861aab72f1cfee3c88a79127d6e2bea8d9b2066f5eb1.png)

# Crew AI News Summary

This repository contains code for a project that utilizes Crew AI to search for news articles, fetch their full text, summarize the articles, and extract keywords.


## Overview

The project consists of the following components:
- **Agents**: Agents are responsible for specific tasks such as searching for news articles, fetching full text, summarizing articles, and extracting keywords.
- **Tasks**: Tasks represent the specific actions to be performed by agents.
- **Data Processing**: The code includes functions to process the fetched news articles, format them, and save the results to a JSON file.

## Project Structure

- **agents.py**: Defines the agents responsible for various tasks.
- **tasks.py**: Defines the tasks to be performed by the agents.
- **news_summary.ipynb**: Jupyter Notebook containing the main code for the project.
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **README.md**: This file, providing an overview of the project.

## Usage

To use the project:
1. Install the required dependencies using `pip install -r requirements.txt`.
2. Set up necessary environment variables or secrets.
3. Run the `news_summary.ipynb` notebook to execute the code and perform the news summary task.

## Dependencies

- [crewai](https://pypi.org/project/crewai/): Python library for building AI-powered workflows.
- [langchain-groq](https://pypi.org/project/langchain-groq/): Python library for using Groq language model.
- [duckduckgo-search](https://pypi.org/project/duckduckgo-search/): Python library for searching DuckDuckGo.

## Contributing

Contributions are welcome! If you have any suggestions, bug fixes, or enhancements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
