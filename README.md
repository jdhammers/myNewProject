# RobotDemo
Robot Framework automated tests project


Selenium Robot Framework Installation with Python & PyCharm

To use Robot Framework with Python, you need to install Python, robot framework, SeleniumLibrary and other supporting libraries.


## Install Python
Go to  https://www.python.org/  install the 3.8.* version
Add Python directory to the Environment Variables Path. (EX: C:\Python3 and C:\Python3\Scripts)


Verify the installed Python version in CMD
`python --version`
Command result should match the installed version (for example: Python 3.8)

Install robot framework with pip command. In CMD run
`pip install robotframework`

Verify the  robotframework version
`robot --version`
Command Result should match the installed version (for ref: Robot Framework 2.8.4 (Python 2.7.6 on win32))


Install DatabaseLibrary
`pip install robotframework-databaselibrary`
Add chromedriver path to the environmental variables PATH
chromedriver is located in the Demo folder, the path to it needs to be added to the Environmental Variables  PATH


## Install PyCharm
Go to https://www.jetbrains.com/pycharm/download/previous.html and install PyCharm Community edition Version 2019.*
Configure PyCharm Settings
Go to Files> Settings>plugins >Browse Repositories for IntelliBot and install


##  Create file associations
To change the file extensions  from  .robot  to .txt
Go to Files> Settings>Editor> File Types> Robot Feature > Add Wildcard *.txt


## Robot framework documentation

http://robotframework.org/robotframework/latest/RobotFrameworkUserGuide.htmlpython 


## SeleniumLibrary documentation

http://robotframework.org/SeleniumLibrary/SeleniumLibrary.html

Please Note: Selenium2Library was renamed to SeleniumLibrary last week, so wherever you see a reference to Selenium2Library, assume SeleniumLibrary, and vice versa.

## To run the tests

`robot path/to/tests/dir/test.txt`