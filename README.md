# Python Web UI Test Framework Template

> Description: This project utilizes a Page Object Pattern/Model emphasizing the strength's of Pytest's Configuration management to make the Framework extensible and maintainable. This project can serve as a great baseline template for the creation of other Web UI Frameworks. 

> Technologies: Python, Selenium, Pytest and Pipenv

> Source: Course by Automation Panda from TestProject.io: https://blog.testproject.io/2019/07/16/python-test-automation-project-using-pytest/

## Installation & Setup

### Clone

- 1st, clone this repo to your local machine at any desired location. Via the Terminal, navigate to the desired directory location where you would like to save this project, then input the following command:
```shell
$ brew install https://github.com/cikent/Python-Web-UI-Test-Framework-Template
```

### Local Setup

#### Step 1 - Directory Customization

1. Change the Folder name to whatever desired (i.e. "Python-Web-UI-Test-Framework-Template" to "My new Python Test Framework")
2. Navigate to the Root of the Folder via the Terminal 

#### Step 2 - Dependency Install

1. Via the Terminal, install **Pipenv**, type:
```shell
pip install pipenv
```

2. Install **Pytest** for the project, type:
```shell
pipenv install pytest --dev
```
This should add two new files to the directory:
- Pipfile
- Pipfile.lock

3. Install **Selenium** for the project, type:
```shell
pipenv install selenium --dev
```

#### Step 3 - Selenium Webdriver Setup

##### Chrome WebDriver Setup

1. If you haven't already, install the latest version of Chrome here: https://www.google.com/chrome/
2. Download the matching version of ChromeDriver respective to the version of Chrome installed: https://sites.google.com/a/chromium.org/chromedriver/
3. Save Chromedriver locally in whatever directory is desired
4. Add Chromedriver to your SYSTEM PATH respective to the Operating System utilized
5. Reboot the Computer
6. Verify Chromedriver is recognized by the system. Via the Terminal, type: 
```shell
chromedriver
```
You should see something similar to:
```shell
Starting ChromeDriver <ChromeDriver Version> (47787ec04b6e38e22703e856e101e840b65afe72) on port 9515
Only local connections are allowed.
Please protect ports used by ChromeDriver and related test frameworks to prevent access by malicious code.
```
Quit ChromeDriver running locally via the Terminal by pressing:
```shell
Control + C
```

##### Firefox WebDriver Setup

1. If you haven't already, install the latest version of Firefox here: https://www.mozilla.org/en-US/firefox/new/
2. Download the matching version of GeckoDriver respective to the version of Firefox installed: https://github.com/mozilla/geckodriver/releases
3. Save GeckoDriver locally in whatever directory is desired
4. Add GeckoDriver to your SYSTEM PATH respective to the Operating System utilized
5. Reboot the Computer

#### Step 4 - Local Setup Verification
1. Navigate to the Root of the Folder via the Terminal
2. Execute the following command:
```shell
$ pipenv run python -m pytest
```
3. The Framework should run. If not, investigate and resolve issues are necessary.

---

## Project Execution

- To run this project, all you have to do is navigate to the respective Root directory where this project was saved locally via the Terminal, then execute the following command:
```shell
$ pipenv run python -m pytest
```

---

## Contact Information

- Email: christopherikent@gmail.com
- LinkedIn: https://www.linkedin.com/in/christopher-kent-9a836631/
