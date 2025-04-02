Political Candidate Polling App
Description
This Django web application is designed to allow users to participate in polls related to a political candidate. The app includes a secure login and registration system, allowing only registered users to participate in polls. The admin site is used to manage poll questions and answers, which are then displayed to users on the front end. The site includes a homepage, an about page, and a polling page where users can view and participate in polls.

Table of Contents
Installation
Usage
GitHub Repository


Installation
Follow these steps to install the project locally:

Clone the repository:
git clone https://github.com/lipholo-dev/Portfolio-Compulsory-Task-2.git

Navigate into the project directory:
cd Portfolio-Compulsory-Task-2

Set up a virtual environment:
python -m venv venv

Activate the virtual environment:

On Windows:
venv\Scripts\activate

On macOS/Linux:
source venv/bin/activate
Install the required dependencies:
pip install -r requirements.txt

Set up the database:
python manage.py migrate

Create a superuser for the admin site:
python manage.py createsuperuser
Follow the prompts to create an admin user.

Run the development server:
python manage.py runserver

The app should now be running locally on your machine. Open your browser and visit http://127.0.0.1:8000/.

Usage
Once the app is running locally, you can access the following features:

Login and Registration: Secure pages for logging in or registering new users.

Polling: Once logged in, users can view and participate in the available polls.

Admin Interface: As an admin, you can add or manage poll questions and answers through the Django admin site at http://127.0.0.1:8000/admin/.

Pages
Home: The landing page of the app with general information.

About: A page containing information about the political candidate.

Polls: A page displaying the available polls for users to participate in.

Login/Register: Pages for logging in or registering new users.

Screenshots
![Screenshot (69)](https://github.com/user-attachments/assets/7624f222-aa21-431d-b578-9090425bb38b)
![Screenshot (68)](https://github.com/user-attachments/assets/9eba541c-55f2-41ad-929b-81416bce6a3a)
![Screenshot (67)](https://github.com/user-attachments/assets/47f66284-5581-48f7-b7a7-41bfb346dc6b)
![Screenshot (66)](https://github.com/user-attachments/assets/5dfac936-5ec3-4f49-8965-a6741c5ceeaf)
![Screenshot (65)](https://github.com/user-attachments/assets/9a744f80-001f-45f3-9cf1-061f6ab1db86)
![Screenshot (64)](https://github.com/user-attachments/assets/86b78d57-4275-482a-8bd5-78abff336699)
![Screenshot (63)](https://github.com/user-attachments/assets/23ed5787-ed02-4030-9422-843e2845bcce)
![Screenshot (62)](https://github.com/user-attachments/assets/0fed52e8-77d7-4777-98aa-b577a3966f35)
![Screenshot (61)](https://github.com/user-attachments/assets/4cd50577-e5fd-498b-a841-d3fac4a573eb)
![Screenshot (60)](https://github.com/user-attachments/assets/0e8ce4a6-dd86-4014-bbba-aa7e1316488f)
![Screenshot (59)](https://github.com/user-attachments/assets/c53b25f2-0e9e-410a-b683-b5d3ba2e314f)
![Screenshot (58)](https://github.com/user-attachments/assets/02abc8c6-7eac-47cb-a96e-d7983b213ddf)
![Screenshot (73)](https://github.com/user-attachments/assets/85cd5f72-fe2f-44c3-b7d9-fc932cd04b23)
![Screenshot (72)](https://github.com/user-attachments/assets/638601b3-92de-4564-aa5d-d9ba451b33ab)
![Screenshot (71)](https://github.com/user-attachments/assets/85f9a99c-0d3a-475f-93ff-862dc2599962)
![Screenshot (70)](https://github.com/user-attachments/assets/1e8374f6-a4dc-435a-8510-cdb222e85bd4)


GitHub Repository
You can find the full project on GitHub: [Political Candidate Polling App Repository](https://github.com/lipholo-dev/Portfolio-Compulsory-Task-2.git)
