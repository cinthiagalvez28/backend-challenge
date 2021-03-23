# Back End Challenge

Todoist API Tests with Postman and Newman.

The purpose of these tests involves the API task module of the Todoist website. The tests were done on the following scenarios:

- Create a new task
- Create several tasks
- Get an active task
- Get active tasks
- Update a task
- Change a task status to 'complete'
- Reopen a task
- Delete a task

## Installation and execution:

Download the zip, unzipped the content, open your favorite IDE and open the project folder. Once inside, open a new terminal and type:

```
npm i newman -g
```

Also, install the reporter:

```
npm i newman-reporter-htmlextra
```


Now, you are set up to run all the tests. Run in the terminal:
```
npm run testAPI
```
This command will initialize all the tests, and will create a report.html in the reports folder of the project. A report is also included if you don't want to run all the tests.

Finally, to run the test that creates several tasks from a csv file, just run in the terminal:
```
npm run test-several-tasks 
```
An html report named SeveralTasksReport.html will be created in the reports folder. To visualize the report just open the html file on chrome and enjoy!

