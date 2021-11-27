### Installation
These instruction will get you a copy of the project up and runing on your local machine

````
> git clone https://github.com/antongrokhovskiy/fortress.git
OR use SSH clone below
> git clone git@github.com:antongrokhovskiy/fortress.git

> npm i - to install modules
> npm test - to run the test and get the results
````

### Architecture
1. Top level - our test file contains all of the assertions for the test and helper methods from the API classes
2. Lower level - API classes contain helper methods that utilize our lowest level abstraction - client
3. Lowest Level - Client that wraps up GET, POST, PUT, DELETE methods