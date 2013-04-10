robot-helpers
=============

A set of keywords created to help with Robot Automation Framework

## SELENIUM 2 FRAMEWORK Helpers 
/selenium2framework

### Keyword: `Open Or Attach To Browser`

Will attached to existing browser window, rather than creating a new one.

Usage:

	*** Test Cases ***
 
	Open Browser
  		Open Or Attach To Browser # Will open browser
 
	Obtain Existing Handle to Browser
  		Open Or Attach To Browser # Will attach to browser