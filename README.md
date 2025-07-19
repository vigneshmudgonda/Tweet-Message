 # Tweet-Message
**Project Title : Tweet Message**

**Description:**
The "Tweet Message" project is a web application built using the Django framework, designed to mimic core functionalities of a microblogging platform. Users can create, view, edit, and delete their own "tweets" (short text messages). The application also supports the inclusion of images with tweets and provides user authentication features, including registration, login, and logout.

**Objective:**
Core Functionality: To provide a platform where authenticated users can post short text messages, optionally accompanied by an image.
User Management: To implement a secure user authentication system allowing users to register, log in, and manage their own content.
**Content Management:** To enable users to easily create new tweets, and to modify or remove their existing tweets.
**User Experience:** To offer a straightforward and intuitive interface for interacting with the tweet functionalities.
**Learning/Demonstration:** To serve as a practical example of building a web application with Django, showcasing features like models, views, forms, templates, and user authentication.

**👥 Team Members:**
    Vignesh Mudgonda

**📸 Screenshots :**

![image alt](https://github.com/vigneshmudgonda/Tweet-Message/blob/d9d11eed23c46c0b55caf7ae62d2f4097b54212f/D1.png)

![image alt](https://github.com/vigneshmudgonda/Tweet-Message/blob/bf80d5e0500f0e215eca802ce53b5d5491df6dd0/d2.png)

![image alt](https://github.com/vigneshmudgonda/Tweet-Message/blob/d32b310125c271b87c97bde1522c1beef88a4e65/d3.png)

**📦 How to run / install :**

#1. Install Dependencies

Install all the required Python packages using pip. While a requirements.txt file isn't provided in the context, the project clearly uses Django. You would typically create one using pip freeze > requirements.txt. For this project, you'll need at least Django and Pillow (for image uploads).
pip install Django==5.2.4 Pillow
# If you have a requirements.txt file:
# pip install -r requirements.txt


#2. Database Migrations

Apply the database migrations to create the necessary tables in your SQLite database.
*python manage.py makemigrations tweet*
python manage.py migrate 

#3. Create a Superuser (Optional, for Admin Access)

To access the Django admin panel, you'll need to create a superuser account:
python manage.py createsuperuser
Follow the prompts to set up your username, email, and password.

#4. Run the Development Server

Start the Django development server:
python manage.py runserver

#5. Access the Application

Open your web browser and navigate to:

http://127.0.0.1:8000/

#6. Register and Log In

Click on "Register" to create a new user account.
After registering, you can log in using your new credentials.
Once logged in, you can start creating, editing, and deleting tweets.

#7. Access Admin Panel (Optional)

If you created a superuser, you can access the admin panel at:
http://127.0.0.1:8000/admin/
Log in with your superuser credentials to manage tweets and users.
