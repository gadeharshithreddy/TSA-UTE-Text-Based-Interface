# TSA-UTE-Text-Based-Interface

# Autoschedule

Autoschedule is a terminal-based task manager that leverages the Gemini API to help users organize and prioritize their work through a natural language interface. Originally developed for the TSA Text-Based User Interface competition, the project focuses on reducing the time spent manually creating schedules while providing a flexible and customizable command-line experience.

## Features

Current functionality includes:

* Natural language schedule generation powered by the Gemini API
* Priority-based task organization
* Configurable schedule settings, including start time and break duration
* Saving and loading schedules for future use
* Editing generated schedules after creation
* Reusing previously entered tasks
* Robust input validation and error handling

## Technologies Used

* Python
* Gemini API
* `python-dotenv`
* `termcolor`
* `wcwidth`

*Add any additional libraries or technologies used by the project here.*

## Installation

### Prerequisites

* Python 3.10 or later
* A Gemini API key

### Setup

1. Clone the repository:

```bash
git clone <repository-url>
cd TSA-UTE-Text-Based-Interface
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the project directory and add your Gemini API key:

```env
GEMINI_API_KEY=your_api_key_here
```

4. Run the application:

```bash
python main.py
```

## Usage

After launching the application, follow the terminal prompts to create and organize your schedule. Autoschedule will guide you through entering your tasks and preferences before generating a prioritized timetable based on your inputs.

*Expand this section with examples of commands, screenshots, or sample workflows if desired.*

## Project Background

Autoschedule was created as a submission for the TSA Text-Based User Interface competition. The project originated from a common challenge faced by students: manually organizing assignments and recurring tasks takes time and is often repetitive. The goal was to develop a command-line application that streamlines schedule creation while remaining flexible enough for day-to-day planning.

## Future Improvements

Potential future enhancements include:

* Additional scheduling customization options
* Improved AI-assisted planning and task recommendations
* Calendar integration
* Recurring task management
* Enhanced terminal interface and visualization

## License

**All Rights Reserved.**

Copyright © Harshith Reddy Gade and Arnav Arora.

This project and its source code may not be copied, modified, distributed, or used without the explicit permission of the copyright holders.
