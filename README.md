# Welcome

## Tasks

### Task 1 - Demonstrate that you can write moderately complex SQLs
![](db/hr_er.png)

 0. http://54.175.245.30:880/phpmyadmin/
 1. Write a query that lists `depart_name`, `city`, `state` , `country`

 ```bash
 +-----------------+---------------------+----------------+------------+
 | department_name | city                | state_province | country_id |
 +-----------------+---------------------+----------------+------------+
 | IT              | Southlake           | Texas          | US         |
 | Shipping        | South San Francisco | California     | US         |
 | Administration  | Seattle             | Washington     | US         |
 +-----------------+---------------------+----------------+------------+
 ```
 2. Write a query that list `employee name` and `manager name`

 ```bash
+------------------+------------------+
| employee         | manager          |
+------------------+------------------+
| Neena Kochhar    | Steven King      |
| Lex De Haan      | Steven King      |
| Alexander Hunold | Lex De Haan      |
| Bruce Ernst      | Alexander Hunold |
| David Austin     | Alexander Hunold |
+------------------+------------------+
 ```
 3. Write a query that list all employees and their department, should also list employees that are not associated with any departments.

### Task 2 - Security
 1. http://54.175.245.30:8080/WebGoat/login.mvc
 2. Show me how you could do basic XSS or SQL Injection.

### Task 3 - Demonstrate that you can write a very simple RESTful webservice
 For this example, we will create a service that manages Departments
 1. Fork this repo
 2. Create a Node.js server that exposes a RESTFul endpoint
    - you can use express.js or any other framework of your choice, no need to persist entities in database, you could return hard-code values.
    - Please feel free to refer to any links, tutorials
    - Demonstrate the functionality using a testcase
 3. Push the repository and give me the link or issue a pull request

### Task 4 - Demonstrate that you can invoke a webservice from Angular or React

 Find the Congressman of your city. For this we will use two publically available service.
  1. Given the city name, find zip codes, make a REST request to zipcodeapi webservice endpoint.ie `https://www.zipcodeapi.com/rest/apikey/city-zips.xml/CITY-NAME/STATE`.
  2. Use a zip code from above result and find legislators, make a REST request to Sunlight congress API endpoint. i.e `https://congress.api.sunlightfoundation.com/legislators/locate?zip=xxxx&apikey=xxxxx`

https://www.zipcodeapi.com/rest/CvHcbOm2blI91DfBOEFQJOYQw4kPzEwbadol1Knc66m8JCJxgon0clQJqbyZQ4b0/city-zips.xml/Chantilly/VA

https://congress.api.sunlightfoundation.com/legislators/locate?zip=20152&apikey=45a77aa041db4ef0887a49a4ac63f05e