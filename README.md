# bootcamp_axios_task
 Structure of the project to prepare the home-task

The task rules.
Repeating the postman collection with a booking via axios and jest.

Install dependencies
```yarn install```

Run tests
```yarn run jest```

Project preparation.
1. Inside the package.json file for you available the basic libraries. Please install it via using command "yarn install". (without "")
2. If you need to install some libraries to your project please install it like devDependencies , it's recommendation if you what to use something new for your project.But by default this is package will be enough


Flow to complete the task:
1. Install the all dependencies to generate the node_modules folder.
2. Add the node_modules folder to git ignore file and ".idea/" too.
3. Inside the folder util ("project_name"/src/util) variables.js file should the repeat you collection variables and globalVariables from postman.
4. Inside the folder util  ("project_name"/src/util) randomGenerator.js file should include the all "data generation scripts" from pre_request tabs postman collection. That is means like date generation future/actual and price generation.
5. Inside the folder test  ("project_name"/src/test) should be located your file with a jest test. The test should be repeated the all tests from your collection. 
6. Inside the folder httpMethods ("project_name/src/httpMethods") please create the files for all your axios requests. One request=one file with a function.
7. Inside the folder bodies ("project_name/src/bodies") please create the preRequest.js file where you will be assigned for some variables which used in  body , value which return your function (like example actualDate ) . That means in this file for checkinDate you shoud assign value from your checkDate function. 
8. Inside the folder bodies ("project_name/src/bodies")  please create the bookingBody.js file where you will be initialized all your bodies which needed for your scenario. And Assign the values from other files inside this boides. Only for depositPaid you can use the static value true/false. Other data should be generated or taken from the varibles file.
9. Try the using the import/export statement. Not the require!
Good luck! =)
