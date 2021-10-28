# String Manipulation
* [Salesforce Formula Reference](https://help.salesforce.com/s/articleView?id=sf.customize_functions.htm&type=5)
* [Salesforce Apex](https://developer.salesforce.com/docs/atlas.en-us.apexref.meta/apexref/apex_methods_system_string.htm)
* [Javascript Methods](https://www.w3schools.com/js/js_string_methods.asp)

## Formula
#### LEFT, RIGHT  
LEFT(text, num_chars)

#### MID  
MID(text, start_num, num_chars) (One-based)

## Apex
#### str.split  
```
String str = 'this-is-test-data';
List<String> res = str.split('-', 2);
System.debug(res);
```
