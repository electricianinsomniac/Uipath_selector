# Uipath_selector
UiPath Studio offers a functionality called selectors which is used to interact with the Graphical User Interface (GUI) elements by identifying their tags and attributes.

## Backgound 
selectors in UiPath Studio. These store the attributes of a graphical user interface element and its parents, in the shape of an XML fragment.

Most of the times, selectors are automatically generated by Studio and do not require further input from you, especially if the apps you are trying to automate have a static user interface.

However, some software programs have changing layouts and attribute nodes with volatile values, such as some web-apps. UiPath Studio cannot predict these changes and, therefore, you might have to manually generate some selectors.

### Case-Sensitive Selectors
Use Casesensitive:"element" and false that 
In order to enable identification of attributes by casing, the case-sensitive() attribute needs to be included in the selector, in the tag of the target attribute

such as:
- casesensitive:<attribute-name>='true' 

*this mean = Enables you to validate a selector by also including an attribute's value casing. By default, the value of this option is set to true.

- casesensitive:<attribute-name>='false' 

*this mean = If set to false, the casing of the attribute's value is not taken into it. it can ignore lowercase or uppercase
