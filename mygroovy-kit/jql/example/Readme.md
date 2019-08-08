This is demo jql function for MyGroovy plugin.


The function finds all tasks upon jql request(as param) and returns them and their sub task.

1) Follow the link {baseUrl}/plugins/servlet/my-groovy/jql/

add script

name: demoJqlFunctionGetTaskAndSubTasks

code: copy paste code from file this package '[demoJqlFunctionGetTaskAndSubTasks.groovy](https://github.com/mailru/jira-scripts/blob/master/mygroovy-kit/jql/demo/demoJqlFunctionGetTaskAndSubTasks.groovy)'

In the code you need to implement one of the classes:
* https://github.com/mailru/jira-plugins-groovy/blob/master/src/main/java/ru/mail/jira/plugins/groovy/api/jql/ScriptedJqlQueryFunction.java 
* https://github.com/mailru/jira-plugins-groovy/blob/master/src/main/java/ru/mail/jira/plugins/groovy/api/jql/ScriptedJqlValuesFunction.java

2) Open jql search: issue in demoJqlFunctionGetTaskAndSubTasks("key in (TEST-39)")   

![demo](https://github.com/mailru/jira-scripts/blob/master/mygroovy-kit/jql/demo/demo%20jql.png?raw=true)