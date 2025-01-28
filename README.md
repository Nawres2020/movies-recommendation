#Movie Recommendation Web App 🎥🍿
Hey there! 👋
I built this web app to provide you with recommendations and detailed information about movies. It's powered by Django on the backend, with HTML and CSS for the frontend.

How to Set It Up on Your Directory 💻
I'll include step-by-step instructions below to help you get it running smoothly in your own environment. 


1/Start by creating a virtual environment
- A virtual environment is essential because it helps you manage dependencies specific to this project, without interfering with global Python packages or other projects on your system. This keeps your development environment clean and reduces the risk of version conflicts.

Here's how to create and activate a virtual environment:

![image](https://github.com/user-attachments/assets/ce5fd15e-255d-4d26-9a21-0b4f4bbe3d0d)


2/After we activate the virtuel environement :
This is on windows 


![image](https://github.com/user-attachments/assets/25970550-2da0-4927-a737-50f9c4e1b920)
# On Linux use 
source venv/bin/activate

this is show that you are in the virtuel environement : 

![image](https://github.com/user-attachments/assets/d9c4a0f5-dc0f-49ef-a8c9-75ce0410155d)

3/Install the required dependencies

- Most likely, all the required dependencies for the project are listed in the requirements.txt file. However, if you need to install additional packages during development, you can do so and then update the requirements.txt file using this command:

"  pip freeze > requirements.txt  "
example of requirement file : 


![image](https://github.com/user-attachments/assets/96d36dbe-3662-440d-8660-14677307a62f)

4/Start the development server
- You can now run the web app locally by starting the Django development server , make sure that you are in the manage.py directory 

![image](https://github.com/user-attachments/assets/1edd78fb-1f42-48a6-8407-667038832ca8)

--> Open your browser and navigate to http://127.0.0.1:8000/ to see the app in action! 🎉

5/Create an Admin User
For our app , only admin can add movies to the list of movies , and thats why you need to have access to the admin panel by creating an admin user 


![image](https://github.com/user-attachments/assets/06fd70eb-c46c-40fc-ab34-4f24f99cd1f8)

Provide Information for the Superuser : 
-Username: Choose a unique username for the admin user.
-Email Address: Enter a valid email address.
-Password: Enter a secure password and confirm it.

Now you can access the admin panel by 127.0.01:8000/admin

![image](https://github.com/user-attachments/assets/09079f72-ef47-48b4-ac2b-23092374d190)

