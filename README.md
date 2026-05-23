# JARVIS Automation

JARVIS Automation is a Python-based framework designed to provide various system and desktop automations, potentially serving as a personal virtual assistant.

## Table of Contents

* Features
* Project Structure
* Getting Started
* Usage

## Features

* **Custom Automations:** The project includes a dedicated module (`Automations.py`) for executing pre-defined tasks[cite: 5].
* **Database Management:** The system utilizes a structured database setup with specialized modules:
* **ChatBot**: Handles conversational logic (`DataBase/ChatBot/ChatBot.py`)[cite: 5].
* **ExtraPro**: Contains utility functions like alarms (`Alarm.py`) and start scripts (`start.py`)[cite: 5].


* **GUI Capabilities:** Includes graphical interface support with components for speed testing (`SpeedTestGui.py`, `SpeedTestUi.py`)[cite: 5].
* **Smart Home/Hardware Integration:** Contains modules for controlling IoT devices, such as smart bulbs (`SmartBulb.py`)[cite: 5].
* **Data Handling:** Provides structured storage for logs and notes (`DataBase/NotePad/`, `DataBase/NasaDataBase/`)[cite: 5].

## Project Structure

The repository is organized into a modular database-driven structure[cite: 5]:

* **`Automations.py`**: The primary script for triggering system tasks[cite: 5].
* **`DataBase/`**: The core directory housing sub-modules[cite: 5]:
* **`ChatBot/`**: Logic and caching for the chatbot feature[cite: 5].
* **`ExtraPro/`**: Additional system tools (Alarm, Tests)[cite: 5].
* **`Gui Programs/`**: Scripts for graphical user interfaces[cite: 5].
* **`HomeAuto/`**: IoT device control modules[cite: 5].
* **`NasaDataBase/`**: Stores data and media related to space imagery and information[cite: 5].
* **`NotePad/`**: Text-based logs and note storage[cite: 5].
* **`OnlineClasses/`**: Modules for managing educational links[cite: 5].
* **`Sounds/`**: Audio resources used by the assistant[cite: 5].
* **`webdriver/`**: Contains browser drivers (e.g., `chromedriver.exe`) for web automation[cite: 5].


* **`run.py` / `start_app.bat**`: Entry points to initialize and run the assistant[cite: 5].

## Getting Started

1. Clone the repository to your local machine.
2. Ensure you have the required dependencies installed (refer to the project's source environment).
3. Ensure your environment is configured to run the automation scripts.

## Usage

1. **Initialize the System:** Use the provided startup scripts to launch the JARVIS environment:
```bash
python start_app.bat
```

2.  **Run Automations:** Interact with the system via the defined automation scripts in the `DataBase/` directory.

