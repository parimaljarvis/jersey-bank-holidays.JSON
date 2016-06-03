# jersey-bank-holidays.JSON
This project exists as I wanted some JSON that contains all the Jersey Channel Islands Bank Holidays so I could reference it for date validation requirement (they didn't want a date selected that was a bank holiday).
Here in the Channel Islands we have an extra bank holiday to celebrate the day we were liberated from German occupation in World War 2.
The UK government have a public JSON file that almost contains all the data required (<a href='https://www.gov.uk/bank-holidays.json'>https://www.gov.uk/bank-holidays.json</a>).
However, it is missing out May 9th Liberation bank holiday.  For reference the legislation that defines Jerseys Bank Holidays is here <a href='https://www.jerseylaw.je/laws/enacted/pages/RO-096-2010.aspx'>https://www.jerseylaw.je/laws/enacted/pages/RO-096-2010.aspx</a>

This small project takes the UK bank holidays JSON and adds our bank holiday into the data so that the result can be manually saved as a JSON file.

* The conversation page is here <a href='http://htmlpreview.github.io/?https://raw.githubusercontent.com/s1m0nj/jersey-bank-holidays.JSON/master/jersey-bank-holidays.html'>jersey-bank-holidays.html</a>
* The JSON that can be used in your project is which is in this file <a href='https://raw.githubusercontent.com/s1m0nj/jersey-bank-holidays.JSON/master/jersey-bank-holidays.json'>jersey-bank-holidays.json</a>. I intended to update this file on a yearly basis, although if anyone does use it feel free to submit a pull request.
* And finally I have a simple test page that has a date control and uses the above JSON as validation which is in this file <a href='http://htmlpreview.github.io/?https://raw.githubusercontent.com/s1m0nj/jersey-bank-holidays.JSON/master/jersey-bank-holidays-validate-example.html'>jersey-bank-holidays-validate-example.html</a>
