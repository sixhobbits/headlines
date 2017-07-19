# Headlines

This is the first example project from my book Flask By Example (https://flaskbyexample.com)

This project focuses on:
* Creating a basic Flask app
* Fetching and consolidating data from various APIs
* Dealing with user input
* Adding cookies in Flask
* Custom CSS

Note that the focus is on education and building things from scratch instead of using blindly using pre-existing frameworks. This code should not be taken as an example of production-ready code.

Note that the code in the book does not encode the information we fetch online as UTF8. On many systems, this will cause Python to try an ASCII encoding, which will throw an error if there are non-ascii characters in the headline or the news summary. Please see https://gist.github.com/sixhobbits/8c27a0f621be225cc301571a7d3f1ec1 for a version that correctly encodes the necessary fields.


