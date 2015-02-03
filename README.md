# Murgi
For converting visual studio .trx file into beautiful html reports

###### What is Murgi ?
Murgi is a python based trx to html convertor using jinja templating engine.

###### Command ?
`python aviconv.py <trxfilename.trx>`
That's all , a report1.html file will be generated which will have everything.

######  How this convertor is different from trx2html and other convertor ?
In visual studio every test method is treated as one test,hence pass fail depends upon the pass/fail of method,
sometimes if a test has multiple test data for example 10, out of which if a single test data fails then whole test method 
is failed, hence this convertor converts based on testdata , for example in a test method if 5 test data passed out of 10 then
result will be shown as 50% pass rather than 0% pass shown by earlier convertors.

>Please feel free to clone>Change>Commit, use it in your projects and let me know in case if it has bugs .
