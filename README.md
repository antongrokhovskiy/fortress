### Installation
These instruction will get you a copy of the project up and runing on your local machine

````
> git clone https://github.com/antongrokhovskiy/fortress.git
> npm i - to install modules
> npm test - to run the test and get the results
````

### Architecture
1. First level - our test file contains all of the assertions for the test and helper methods from the API classes
2. Second level - API classes contain helper methods that utilize our lower level abstraction client methods which is a wrapper for GET, POST, PUT, DELETE methods