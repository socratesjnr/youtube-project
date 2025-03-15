# youtube-project

Exploring Youtube to derive valuable insights for the data community

## Project Description

This project aims to explore Youtube as video sharing company to derive some insights that can be useful to the data community. We plan to use Python and Power BI for data analysis and visualization, and will collect data via Youtube API. The project will consist of four phases: planning and preparation, data collection and preparation, modeling and analysis, and reporting and presentation.

## Table of Contents

- [youtube-project](#youtube-project)
  - [Project Description](#project-description)
  - [Table of Contents](#table-of-contents)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Installing](#installing)
    - [Contributing](#contributing)
  - [Data Collection](#data-collection)
  - [File Structure](#file-structure)
  - [Authors](#authors)
  - [Acknowledgments](#acknowledgments)

## Getting Started

### Prerequisites

To run the code for this project, you will need to have the following software installed on your computer:

- Python 3
- Jupyter Notebook
- Power BI

### Installing

- Clone this repository to your local machine
- Install the required packages by running the following command in your terminal: pip install -r requirements.txt
- Open the Jupyter Notebook files to run the code and perform data analysis
- Open the Power BI file to visualize the data

### Contributing

To contribute to this project, please read the [contribution guidelines](CONTRIBUTING.md). Also check out the [code style guide](CODE_STYLEGUIDE.md) and the [visualization style guide](VIZ_STYLEGUIDE.md) for details on what we expect.

## Data Collection

We will be using Youtube API to collect data needed for this analysis. 

## File Structure

```python
youtube-project
│   README.md               # Project description and instructions
│   CONTRIBUTING.md         # Guidelines for contributing to the project
│   CODE_STYLEGUIDE.md      # Guidelines for code style and formatting
│   LICENSE.md              # License for the project
|   .idea                   # Directory to store project-specific settings
│   .gitignore              # Files and directories to be ignored by Git
│
├── mailing
│   ├── bounced_email_address.csv     # Invalid mails
│   ├── student_distribution.ipynb   # Distribution of student mails
│   ├── student_mails.csv            # File containing the student mail
│   └── valid_student_mails.csv      # Mailing list
│
├── mock analysis
│   ├── sample.csv                # Raw data collected from Google Forms
│   ├── expanded_sample.csv       # Cleaned and expanded data for analysis
│   ├── test_eda.ipynb            # Jupyter Notebook for exploratory data analysis
│   ├── test_modeling.ipynb        # Jupyter Notebook for modeling and analysis
│   ├── test_dashboard.pbix        # Power BI file for visualizing the data
│   └── README.md                 # Description of the mock analysis folder
│
├── team-management
│   ├── assigned_roles.csv        # Roles assigned to team members
│   ├── role_assignment.ipynb     # Jupyter Notebook for assigning roles to team members
│   └── role_summary.csv          # Description of roles
│
└── project analysis
    ├── data
    │   ├── raw_data.csv           # Raw data collected from Google Forms
    │   └── cleaned_data.csv       # Cleaned data ready for analysis
    ├── analysis
    │   ├── exploratory_data_analysis.ipynb   # Jupyter Notebook for exploratory data analysis
    │   └── modeling.ipynb          # Jupyter Notebook for modeling and analysis
    ├── results
    │   └── dashboard.pbix          # Power BI file for visualizing the data
    ├── requirements.txt            # Required Python packages for the project
    └── README.md                   # Description of the project analysis folder

```

## Authors

- [Oluwaseyi Adaramola](http://github.com/socratesjnr)

## Acknowledgments

This project was inspired to explore the impact of Youtube videos to the data community as a whole.
Thanks to the team members who contributed to this project
