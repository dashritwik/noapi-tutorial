
# NOAPI Tutorial

Noapi is a light API framework for Node.js. It can easily define APIs and test cases, as well as easily read inputs/outputs and test them. Noapi takes care of the required web services, api services, routes, test cases, and etcetera to help you focus on functional code, improve your efficiency, and save your time.


# Audience

This tutorial has been created for anyone who has basic knowledge of Nodejs and Expressjs and how client-server works after completing this tutorial you can define APIs and test cases, as well as easily read inputs/outputs and test them

In this tutorial, you will learn-



*   Installing noapi and using noapi  we will define a simple API route 
*   Test APIs with noapi
*   Create custom Express Server
*    Router to handle Request

    **Installing and using noapi**


    Noapi gets installed via the node package manager, this can be done by executing the following line in the command line but before installing noapi we need  package.json file for this run the following command:


    ** npm init**


    ** **and answer the questions in the command line questionnaire


    

![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo2.png)





    **npm install noapi **


    The above command requests the Node package manager to download the required noapi modules and install them accordingly**.**


    Let's use our newly installed noapi framework and create a simple "Hello World" application


      **Step 1:** create app.js file where we will define our server  and open it on your favorite text editor in this tutorial I’m using Vscode


    


![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo3.png)



    **Step 2: **Create an API folder and inside this folder create a file called define.js in this file we will define our API routes


    


![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo5.png)



    **Step 3**:  now we need to start our server for that run this following command on your command line** node . **(server will automatically run on default port 3000)


    

![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo6.png)



    **Step 4:** Open your favorite browser  and enter this URL and enter [http://localhost:3000/hello](http://localhost:3000/hello)


    


![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo7.png)



    **Congratulation **we successfully completed our first step stage 


**Test API with noapi**


    To test our API  we have to install  some dependencies which will help us to test our API faster


    We need following these dependencies 1:chai,2:moacha,3:supertest


    **Step 1**: Install dependencies, run this command **npm install chai mocha supertest -D**(D flag means these packages are dev-dependencies)


    **Step 2: **Create a folder called biz in this folder we will write our business logic and inside this folder create a file called hello.js


    


![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo9.png)



    **Step 3**:we need another folder to test our API which is called test and inside this folder create file called index.js


    

![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo10.png)


    **Step 4**: now open package.json file and replace the `scripts`


     test 


    

![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo11.png)



    **Step 5**: final step to test our API open your terminal from your project root folder and enter **npm test **(stop if there is any server running on port 3000)


    

![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo13.png)



## **Create custom noapi Server**

So far  we have been using default server settings now we are going to use noapi custom server settings

**Step 1**:  open app.js file 



![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo13a.png)


Here configured basic settings of noapi

**Step 2**:  let’s start the server again **node app.js **(also you could so **node .**)



![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo14.png)


We successfully configured noapi


## ** Router to handle Request**

Here we are going to see how to could handle client request

 **Step 1:** to handle the request we need to define a route, open your define.js




![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo16.png)


**Step 2**:open the biz folder and create a called about.js




![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo15.png)


**Step 3: **Start the server again **node app.js**




![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo6.png)


**Step 3: **open browser and hit http://localhost:3000/about URL




![](https://github.com/dashritwik/noapi/blob/master/doc/images/demo18.png)



    What we have learned from this  tutorial


     1: how to install noapi and setup


    2: how easily we could define our API 


    3: how we could test our API without writing tonnes of line code


    4: how we could change the default server setting 


    5: how we could write our own custom express routes.
