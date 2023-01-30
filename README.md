# xml
eXtensible MarkUp Language code

## XML Basics

XML is a DDL/Data Description Language;  
and, as such, it is very good at, carefully, 'categorising' data;  
this is because it allows one to both invent/and, name your 'own' tags...;  
therefore, you are free to adapt XML tags entirely to suit whatever is your own specific purpose/needs.  

For example, let us say you wanted to create a 'phonebook' application;  
then, you could invent your own root-tag called: phonebook.  

&lt;root-tag-name-pair&gt;  
-(all the rest of your XML tags goes inside here...)-  
&lt;/root-tag-name-pair&gt;  


&lt;phonebook&gt;    

&lt;entry number="1"&gt;    
&lt;name&gt;Jack&lt;/name&gt;    
&lt;number&gt;1111 111 1111&lt;/number&gt;    
&lt;/entry&gt;    

&lt;entry number="2"&gt;    
&lt;name&gt;Jill&lt;/name&gt;    
&lt;number&gt;2222 222 2222&lt;/number&gt;    
&lt;/entry&gt;    

&lt;/phonebook&gt;    
  
XML, uses very 'strict' rules...;   
- all paired tags needs to be closed, properly, with a forwards facing slash;    
- each single tag needs to be closed, properly, with a forwards facing slash;     
- each attribute/value pair needs to have a pair of double quotes around it.
- other tags can repeat...; but there must be only 'one' root tag pair;  
- etc.  

-(**NOTE**: These XML rules can each be 'enforced' by using a XML DTD/Document Type Definition document.)-      

-----

## OTHER XML TECHNOLOGIES

Just like HTML is not a stand alone technology...; but, also, includes such things as CSS/Javascript/-etc.  

XML, has a number of additional technologies tacked onto it, too:- 

- DTD/XSD
- XSL/XSLD
- XML/CSS stylesheet
- XPointer
- XQuery
- XLink
- etc.

...in addition to which there are specific editors for both creating/testing/and, developing XML.  

And, that's not to mention the many spin off technologies that are based on XML...

- SVG, Scaleable Vector Graphics  
- RSS, Really Simple Syndicate  
- etc.

-----

## Links

### Tutorials


