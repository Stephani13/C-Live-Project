# Live Project


## Introduction

In the last two weeks of my time in the tech academy, I worked with a team in developing a full scale Web Application in C#, using ASP.Net MVC. Working on such large project was a big learning oportunity for me by fixing bugs and adding the requested features. I worked on some front end stories that allowed me to use my creative ideas to reach to the desired outcome. 

Here are some description of the stories I worked on, along with code snippets:

## Entity Model


This model creates a table to store information about the cast members. My goal was to create the table and add it to an existing database to display in the screen for the user to view. First I created the properties and then using Entity Framework to scaffold CRUD pages, I added CRUD funtionality used the create page to gather the information from user and then render it on the index page from the cast member side. The information could be also edited using the edit page or deleted.

![Screenshot (6)](https://user-images.githubusercontent.com/94413603/165442970-923d7a9b-4951-4290-bb9e-9d34079f1850.png)


## Create and Edit

In this task, I had to do some styling to the create and edit pages to atch the team on the project. So to accomplish this I added some classes and in-line styling to use in my CSS.


![Screenshot (7)](https://user-images.githubusercontent.com/94413603/165442951-e8515fae-4360-4bc1-989e-dc2adac8503b.png)


CSS:

![Screenshot (8)](https://user-images.githubusercontent.com/94413603/165442935-15730198-bdef-4f20-a543-deca79236da7.png)



![Screenshot (9)](https://user-images.githubusercontent.com/94413603/165442942-c110a82b-79db-443d-9d79-cbe5519e6663.png)



## Fix Buttons

Another of the task given was to fix the buttons for log in and register to make it look clean and nice with no text styling, it used to have a link underlining.


![Screenshot (10)](https://user-images.githubusercontent.com/94413603/165443363-4f9ab06c-1c47-467c-b912-067396105823.png)



## Photo Storage and Retrieval

Lastly, I was to allow the user to upload a picture and store it on the database. To be able to do this I had to convert the the HttpPostedFilesBase to byte[] to be able to store it. And then be able to retrieve it for user to view, by doing the opposite conversion.


Convertion to bytes and storage on database:
![Screenshot (11)](https://user-images.githubusercontent.com/94413603/165443691-3418b9ff-d501-4e4b-817b-798eb2d39da8.png)
![Screenshot (12)](https://user-images.githubusercontent.com/94413603/165443785-9dd303fb-5313-428f-bf2f-74b24b73513c.png)

Create a field on create page:
![Screenshot (13)](https://user-images.githubusercontent.com/94413603/165443792-592a11b9-4bc9-4197-8a69-600d20551120.png)

Convert back to the image to display on index page:
![Screenshot (14)](https://user-images.githubusercontent.com/94413603/165443839-d05b2687-50cb-46ae-a123-76a32d0806a2.png)
