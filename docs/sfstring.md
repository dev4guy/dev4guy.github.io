# String Manipulation
* [Salesforce Formula Reference](https://help.salesforce.com/s/articleView?id=sf.customize_functions.htm&type=5)
* [Salesforce Apex](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_methods_system_string.htm)
* [Javascript Methods](https://www.w3schools.com/js/js_string_methods.asp)

## Formula
### LEFT, RIGHT  
LEFT(text, num_chars)
```
TRIM(LEFT(LastName, 5)) & "-" & TRIM(RIGHT(SSN__c, 4))
This formula displays the first five characters of a name and the last four characters of a social security number separated by a dash. Note that this example uses a text custom field called SSN.
```
### MID  
MID(text, start_num, num_chars)
```
MID(Division, 3, 4) returns four
```
