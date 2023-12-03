# selenium-testing-demo
This project is related to selenium testing demo for beginner. 
# Author - Pawan Gupta
# 1 . XPath- 
    1. //Tagname[@attribute='value']
	example - 
	<input type="text" placeholder="Name">
	XPath- //input[@placeholder='Name']
How to check element in conole 
	$x('//input[@placeholder="Name"]')
How to handle multiple xpath -
using indexing we canhandle 
 syntax - //input[@placeholder='Name'][2]
# 2.CSSSelector 
        1. Tagname[attribute='value']
	example - 
	<input type="text" placeholder="Name">
	CSSSelector- input[placeholder='Name']
How to check element in conole 
	$('input[placeholder="Name"]')
How to handle multiple cssSelector -
using indexing we canhandle 
 syntax - input[placeholder='Name']:nth-child(2)

