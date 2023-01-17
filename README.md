# PyTest/Pylenium Tutorial with Selenium
Let's look at how to use Pylenium for UI test automation.  

## Get Started
```
mkdir selenium_pytest_demo
git init 
git clone https://github.com/Eugene-Kwaka/Selenium-Pytest-Demo.git
cd Selenium-Pytest-Demo
py -m venv seleniumpytestdemoenv
seleniumpytestdemo\Scripts\activate.bat
pip install -r requirements.txt
mkdir tests
cd tests
create a __init__.py file
```
click on CTRL+SHIFT+P and type Python:Configure Tests. Then click on tests


## On The Terminal
To initialize pylenium, write the command:
``` 
pylenium init 

```
To run the tests.
```
py -m pytest tests/test_example.py

```
