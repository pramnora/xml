# xml
eXtensible MarkUp Language code

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
&lt;/phonebook&gt;    
  
XML, uses very 'strict' rules...;   
- all paired tags needs to be closed, properly, with a forwards facing slash;    
- each single tag needs to be closed, properly, with a forwards facing slash;     
- there can only be just 'one' root tag pair;  
- each attribute/value pair needs to have quotes around it.
- etc.  
  
