# Lab 8 Group 6
## Project Name: Auto Attendance System
### Testing for registration and login functionality

### Student Login Functionality
Test Cases:
**Email**
<ul>
<li>
<strong>Email</strong> = “”, <br> <strong>password</strong> = “<password>” 
<br>
<strong>Expected Output</strong>: to show the error message


![image](https://user-images.githubusercontent.com/122982846/233130325-3dbc2c36-418b-471c-8181-a5726be434fc.png)
<strong>Status</strong>: failed
<strong>Solution</strong>: In the field of email we forget to put the “required”, so to solve this we typed “required” in input tag.
![image](https://user-images.githubusercontent.com/122982846/233130843-6652eaf8-b200-4240-a157-7d42e9dabe49.png)
 </li>
 <li>
<strong>Email</strong> = “email”, <br> <strong>password</strong> = “” 
<br>
<strong>Expected Output</strong>: Shows the prompt to fill the required field.


![image](https://user-images.githubusercontent.com/122982846/233131868-16b67ce5-385f-4bf8-bc9c-9ec11e753a41.png)
<strong>Status</strong>: Pass
 </li>
 
<li>
<strong>Invalid Email format</strong>
<br>
<strong>Expected Output</strong>: To show the prompt for invalid email format

 ![image](https://user-images.githubusercontent.com/122982846/233132814-671d9df4-c8fd-4097-8d83-f10bbbf529a6.png)

<strong>Status</strong>: passed
<br>
</li>

<li>
<strong>When the email is in wrong format and password is empty. </strong>
<br>
<strong>Expected Output</strong>: Show the prompt to type in correct format.

![image](https://user-images.githubusercontent.com/122982846/233135159-8bbae817-42a6-4e42-9b69-8f1c00c0af8f.png)

<strong>Status</strong>: Pass
<br>
</li>


<li>
<strong>When email is in correct format and password is incorrect.</strong>
<strong>Expected Output</strong>: render the same page again.
<br>

![image](https://user-images.githubusercontent.com/122982846/233142654-0459e9be-f32b-4376-92ef-f4ea602e0f91.png)

<strong>Status</strong>: passed
<br>
</li>

<li>
<strong>When email is correct format and password is also correct.</strong>
<strong>Expected output</strong>: show student dashboard.
 
 ![image](https://user-images.githubusercontent.com/122982846/233142477-45270307-c837-4b0e-a26a-a35cde97d2cb.png)

<strong>Status</strong>: passed<br>
</li>
</ul>















#### Instructor Login functionality
Test Cases:
<ul>
<li>
<strong>Email</strong> = “”, 
<br>
<strong>password</strong> = “<password>” <br>
<br>
<strong>Expected Output</strong>:to show the error message<br>

 ![image](https://user-images.githubusercontent.com/122982846/233141302-b6ee9704-22ae-4359-91f9-9bee90f3f0d0.png)
<strong>Status</strong>: failed

<strong>Solution</strong>: In the field of email we forget to put the “required”, so to solve this we typed “required” in input tag.<br>

 ![image](https://user-images.githubusercontent.com/122982846/233141372-bdf8c1ed-7918-4fe3-863a-32a360a3bdc5.png)

<li>
<strong>Email</strong>: ""<br>
<strong>Password </strong>: “”<br>
<strong>Expected Output</strong> : Shows the prompt to fill the required field.<br>
</li>

![image](https://user-images.githubusercontent.com/122982846/233142986-f5272b42-1392-4387-b38b-4e990ae1c240.png)
<strong>Status</strong>: passed<br>
<li>
<strong>Invalid Email format</strong><br>
<strong>Expected Output</strong>: To show the prompt for invalid email format<br>

 ![image](https://user-images.githubusercontent.com/122982846/233142995-170945e6-b244-4213-9956-a7011d2a118e.png)
<strong>Status</strong>: passed<br>



<li>
<strong>When the email is in wrong format and password is empty.</strong><br>
<strong>Expected Output: Show the prompt to type in correct format.</strong><br>

![image](https://user-images.githubusercontent.com/122982846/233143013-48c031a8-ffdb-408b-b0f3-8dfc7451a3bf.png)
<strong>status</strong>: Pass<br>

<li>
<strong>When email is in correct format and password is incorrect.</strong><br>
<strong>Expected Output</strong>: render the same page again.<br>

 ![image](https://user-images.githubusercontent.com/122982846/233143029-7c2c1356-fdac-4de4-91b7-eb3278be80af.png)

<strong>Status</strong>: passed<br>
<strong>When email is correct format and password is also correct.</strong><br>
<strong>Expected output</strong>: show instructor dashboard.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143054-4667ff0c-4d5a-48cc-860a-8fab487093ef.png)

<strong>Status</strong>: passed<br>

### Student Registration functionality
<li>
<strong>First name</strong>: empty<br>
<strong>Other input fields are valid and not empty</strong><br>
<strong>Expected output</strong>: Prompt showing <br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143065-cd7e2b63-6281-4b22-bdde-2fdeaa5c217a.png)

<strong>Status</strong>: passed<br>
<strong>Last Name field empty and other fields are valid.</strong><br>
<li>
<strong>Expected</strong>: Prompt to enter last name.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143178-9ae40963-ce75-485f-8ed4-f3d3d260bb28.png)

<strong>Status</strong>: passed<br>
<li>
<strong>When email is not in correct format.</strong><br>
<strong>Expected Output</strong>: Prompt to enter correct email.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143203-5983558d-3a98-4f6c-8a7f-0c88f86f3889.png)

<strong>Status</strong>: passed<br>
<li>
<strong>Entering email already exists</strong><br>
<strong>Expected Output</strong>: Redirect again to the register page.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143227-4117ebd3-b70a-4663-a2d8-34a0fe5b5a6f.png)

<strong>Status</strong>: Passed<br>
<li>
<strong>When all fields are empty.</strong><br>
<strong>Expected Output</strong>: Prompt to fill required field.<br>

![image](https://user-images.githubusercontent.com/122982846/233143257-def0b859-6f81-48fd-a8e1-8d129689306c.png)

<strong>Status</strong>: Passed<br>
<li>
<strong>When valid entries are entered</strong><br>
<strong>Expected Output</strong>: Redirect into login page<br>

 ![image](https://user-images.githubusercontent.com/122982846/233143280-8b576b9c-5f2e-4612-85b9-9277ae64839f.png)

<strong>Status</strong>: Pass<br>



### Instructor Registration functionality<br>
<li>
<strong>First name:</strong> empty<br>
<strong>Other input fields are valid and not empty</strong><br>
<strong>Expected output</strong>: Prompt showing <br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143300-0f13444e-8af9-40dc-8ce3-7d07913c0385.png)

<strong>Status</strong>: passed<br>
<strong>Last Name field empty and other fields are valid.</strong><br>
<strong>Expected</strong>: Prompt to enter last name.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143313-6cda5357-1947-4367-9aaa-97f29294af3f.png)

<strong>Status</strong>: passed<br>
<li>
<strong>When email is not in correct format.<br>
Expected Output: Prompt to enter correct email.</strong><br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143331-2007c22e-7a41-4433-b3f3-39cf8559b877.png)

<strong>Status</strong>: passed<br>
<li>
<strong>Entering email already exists</strong><br>
<strong>Expected Output</strong>: Redirect again to the register page.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143349-a4942dd2-519e-42b5-80fc-b09a4b285c54.png)

<strong>Status</strong>: Passed<br>
<li>
<strong>When all fields are empty.</strong><br>
<strong>Expected Output</strong>: Prompt to fill required field.<br>
 
 ![image](https://user-images.githubusercontent.com/122982846/233143375-4a6d1664-ab17-401b-9a81-410d44081d70.png)

<strong>Status</strong>: Passed<br>
<li>
<strong>When valid entries are entered</strong><br>
<strong>Expected Output</strong>: Redirect into login page<br>

![image](https://user-images.githubusercontent.com/122982846/233143391-4105f896-a3f1-4b38-a914-0bc9bb5d12bf.png)

<strong>Status</strong>: Passed<br>

