This is a test client for [my noisy-apitest](https://github.com/danielruss/noisy-apitest).  
The API randomly throws server errors, this test stores results when it sees a 500 error and resends
the parameters next time you click "call api".  Since the form only has two text boxes with fixed keys,
I append a date to each key so that the values are unique.  When the API is successful, ALL values are displayed
on the web page.  The cache is then cleared.
