## My Backend step by step procedure implementation

1. npm init
2. .gitigonre is created and "<https://mrkandreev.name/snippets/gitignore-generator/#Node>" content is pasted inorder to ignore node sensetive data
3. In package.JSON we added "type":"module", just below description

4.

### NOTE : When server file is reloded then we should do off and on server

To handle it:
A. There is --watch in node.js but is is not widely used in production grade
B. We will use nodemon
                When ever we save the file it restart on the server
                Node mon have dev dependency
                DEV DEPENDENCY IS ONE WHICH IS USED DURING DEVELOPMENT NOT IN PRODUCTION

### npm i nodemon

                -->It will main dependency

### npm install --save-dev nodemon

### npm install -D nodemon

                -->It will add node_modules folder in the project

                -->Look at package.JSON,the added line is ::"devDependencies": {
                                                        "nodemon": "^3.1.3"
                                                             }
