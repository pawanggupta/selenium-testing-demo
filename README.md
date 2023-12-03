# selenium-testing-demo
This project is related to selenium testing demo for beginner. 
# Author - Pawan Gupta
# 1 . XPath- 
    A).Syntax 1. //Tagname[@attribute='value']<br/>
    example - <br/>
	<input type="text" placeholder="Name">
	XPath- //input[@placeholder='Name']
    B).How to check element in console <br/>
	$x('//input[@placeholder="Name"]')
    C).How to handle multiple xpath <br/>
         using indexing we canhandle <br/>
         syntax - //input[@placeholder='Name'][2]
# 2.CSSSelector 
        A).Syntax 1. Tagname[attribute='value'] <br/>
	    example - <br/>
	    <input type="text" placeholder="Name"> <br/>
	    CSSSelector- input[placeholder='Name'] <br/>
        B).How to check element in console <br/>
	     $('input[placeholder="Name"]')
        C). How to handle multiple cssSelector -<br/>
            using indexing we canhandle <br/>
             syntax - input[placeholder='Name']:nth-child(2)

