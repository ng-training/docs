## RxJs

1. Filter the employee list:
- add a new input of type checkbox to employee list component “Show only devs”
- map the state changes to a Subject
- merge it with the Observable from search
- filter the employees in the subscribe handler of the new stream and pass both the search string and the boolean state of the checkbox

[Next exercise](9-http.md)
