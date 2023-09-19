# ScheduleToCalendar

Automatically convert your school's hard-to-read schedule from the website into your Google Calendar.

## Table of Contents

- [ScheduleToCalendar](#scheduletocalendar)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Installation](#installation)
    - [Prerequisites](#prerequisites)
    - [Installation Steps](#installation-steps)
  - [Usage](#usage)
    - [Windows](#windows)
  - [License](#license)
  - [Acknowledgments](#acknowledgments)

## Project Description

Do you find your school's website schedule a headache to read? This project aims to simplify your life by converting your school schedule into Google Calendar events.

**Note:**
- This project is a work in progress.
- Google Calendar API credentials and configurations are not included in this script.

<!-- By now, `ScheduleToCalendar` supports below schools:
- SGU ([Saigon University](https://www.sgu.edu.vn/))
- HUFLIT ([HCMC University of Foreign Languages - Information Technology](https://huflit.edu.vn/)) -->

## Installation

### Prerequisites
- [Python](https://www.python.org/) >= 3.10
- Required packages listed in `requirements.txt`.
- The `credentials.json` file in the `api` folder.

### Installation Steps
1. Clone this repository.
   ```bash
   git clone https://github.com/tuananhphann/ScheduleToCalendar.git
   cd ScheduleToCalendar
   ```

2. Install the required packages.
   ```bash
   pip install -r requirements.txt
   ```

3. If you do not have any credentials to interact with Google APIs, please follow this [link](https://developers.google.com/workspace/guides/create-credentials#desktop-app) to create them. Note that the application type should be set to `'Desktop app'`.

## Usage

### Windows
In the project directory, run this command
```powershell
python .\main.py
```
Then follow the prompts.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments
Thanks to ChatGPT helped me create the README.md file.
