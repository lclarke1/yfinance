OBJECTIVE
Yfinance is a historical market data downloader that was created in response to Yahoo Finance decomissioning their historical data api. 
The objective of this project is to test the get_json function in utils.py of the yfinance software.
The get_json function in utils.py one of the main functions that gets the market data from yahoo, so the tests will be centered around confirming that 
this function is working correctly and we are actually able to downlaod market data form yahoo in json format using the get_json function

TEAM MEMBERS
lclarke1

RESEARCH AND PLANNING
There was only 1 issue and 1 pull request related to the get_json function identified during the research phase. 
The issue identified looks to be a error caused by using an older version of python and was resolved in a later version of yfinance
The pull request addressed an error caused when yfinance attempts to get market data from Yahoo Finance where the ticker for that data does not have
the same fields as the data request, which causes an error. The pull request included a soltution to this error and was merged and closed.

LIST of PLANNED TEST
unittest.get_json_testcase1

RISKS INVOLVED
There do no appear to be any risks involved in testing this function

TEST APPROACH
A test will be written to test the get_json function in utils.py, this test will confirm that the get_json function works as intended. 

TEST ENVIRONMENT
Unittest





