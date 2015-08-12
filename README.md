## Installation

### 1. Clone the Repository

* Enter the directory that you use for git projects, then run:
  ```bash
  $ git clone https://github.com/karishay/advocate_calculator
  ```

### 2. Set up your Virtual Environment

* Install virtualenv. 
  ```bash
  $ pip install virtualenv
  ```
* Create the virtual environment by navigating to your project folder and running:
  ```bash
  $ virtualenv venv
  ```
* You should have your virtual environment active while working on this project. To activate it, enter:
  ```bash
  $ source venv/bin/activate
  ```
* While your virtual environment is active, install the project's python dependencies with:
  ```bash
  (venv) $ pip install -r requirements.txt
  ```
* If you made a change to the project's dependencdies, run this in your virtual environment before committing:
  ```bash
  (venv) $ pip freeze > requirements.txt
  ```
* Don't forget to deactivate your virtual environment when you're done working in the repository. To do so, simply run: 
  ```bash
  (venv) $ deactivate
  ``` 

### 3. Install the WebDriver for Chrome

* Download the latest chromedriver release [here](https://sites.google.com/a/chromium.org/chromedriver/downloads).
* Extract the .zip file and place the chromedriver executable in a safe location, where it will not need to move. 
* Append the line `export PATH_TO_CHROMEDRIVER='/the/path/to/chromedriver'` to your `~/.bash_profile` or `~/.bashrc` file (where */the/path/to/* is the full path to where you placed the the chromedriver executable).