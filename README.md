# selenium-testing-demo
This project is related to selenium testing demo for beginner. 
# Author - Pawan Gupta
# 1 . XPath- 
    A).Syntax 1. //Tagname[@attribute='value']
        example -
	   <input type="text" placeholder="Name">
	    XPath- //input[@placeholder='Name']
    
    B).How to check element in console 
	    $x('//input[@placeholder="Name"]')
   
    C).How to handle multiple xpath 
            using indexing we can handle
            syntax - //input[@placeholder='Name'][2]
	    
# 2.CSSSelector 
        A).Syntax 1. Tagname[attribute='value']
	        example-
	        <input type="text" placeholder="Name">
	        CSSSelector- input[placeholder='Name']
	 
        B).How to check element in console
	      $('input[placeholder="Name"]')
       
        C). How to handle multiple cssSelector
                using indexing we canhandle
                syntax - input[placeholder='Name']:nth-child(2)

