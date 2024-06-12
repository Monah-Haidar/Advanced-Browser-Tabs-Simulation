
# Advanced Browser Tabs Simulation

## Description
This Python application simulates advanced browser tab operations via a command-line interface. It allows users to perform various tasks such as opening, closing, and switching between tabs, managing nested tabs, and more, utilizing a simple menu-driven approach.

## Features
- Open a new tab by specifying the title and URL.
- Close a specific tab or the last opened tab if no index is provided.
- Switch between tabs to display their content.
- View all open tabs, including nested tabs, in a hierarchical order.
- Add nested tags within an existing tab.
- Save the current state of all tabs to a file in JSON format.
- Import tabs from a JSON file to restore their state.
- Clear all opened tabs.
- Exit the application.

## Installation
To use this application, Python must be installed on your machine. Clone or download this repository to your local environment and navigate to the project directory.

```bash
git clone [repository-url]
cd [repository-directory]
```

## Usage
To start the application, execute the following command in the terminal:

```bash
python main.py
```

Follow the on-screen instructions to choose from the menu options and interact with the system.

## Dependencies
- `selenium`: Needed for fetching and displaying HTML content of web pages.
- `validators`: Used for URL validation when opening new tabs.

Install these dependencies using pip:

```bash
pip install selenium validators
```


