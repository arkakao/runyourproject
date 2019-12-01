RunYourProject

This project is to organize and arrange student projects with their professors.

Usage:

When you clone it, put the master folder to your web server directory.
Then, import the `RunYourProject.sql` file to your mysql database.
By default, it will create a new database called as `RunYourProject` with the tables. 
In case if it does not work, you can use `RunYourProjectTable.sql` to import only the tables into the database you created.
By default, it will only create a student profile.
In order to create a professor account, you have to create a user as usual.
Then, change `type` to `1`. To enable a project, you have to change `status` to 1 in `project` table.


Website usage:
First enter your username and password and click sign in.
If you dont have an username and password click sign up.
In sign up page, fill out all the blanks.
After you created yopur account please login.

You are going to see your projects.
Available projects.
Project requests.
If you don't have any project, in the footer there is a 'Create a project' button.
Click Create a project button
Fill out, Project Name,Project Description,Project Country,Select Project Year
Click create
Now your project request is created.


For Professor side,
You are going to see available projects
Project requests
And assign button
Click assign button
Select user and available project and click update then 
Add user and project id to insert the project to the user

That's how you runyourproject :)
