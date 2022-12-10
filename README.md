Django-TailwindCSS Appointment System  



https://user-images.githubusercontent.com/38588709/206873738-eccbca0e-b9db-4810-b49e-3c6ca646d1e4.mp4



-------------------------------------------------------------------------------------------------------------------------------
FEATURES
-------------------------------------------------------------------------------------------------------------------------------

Overview (Auth)
- User's can register directly on the app or can login using social network. 
- After authenticated user's will need to complete their profile (choose their doctor,writting their bio etc)
- If registered user is a doctor , then it will need first to create a profile and after the admin 
will need to upgrade the account from django administration.

Overview (Dashboard) 
- User's here can see their profile and basic things about their doctor profile. 
- Can create appointments. *(They can reserve dates from the date today and after 1 month,they can't select sunday or saturday)
- Can see avaiability. (Can select avaiabile date,see reserved appointments and convert them to excel)

Overview (Doctor Dashboard) 
- Can view the total number appointments reserved with him, number of appointments for each day.
- Can convert patients list into excel 
- Can convert upcoming appointments into excel 
- Can delete appointments 

Overview (Doctors) 
- It contains the models (Doctor, Appointment, Profile)

-------------------------------------------------------------------------------------------------------------------------------
USEFUL INFORMATION
-------------------------------------------------------------------------------------------------------------------------------

Running app with ssl certificate : python manage.py runserver_plus --cert-file cert.pem --key-file key.pem 

Running app without ssl certificate : python manage.py runserver 

Starting tailwind : python manage.py tailwind start 

Login credentials for admin 
USERNAME : admin
PASSWORD : admin 

Login credentials for doctors 
USERNAME : ubaldalorenza 
PASSWORD : django123

USERNAME : kaivrtek
PASSWORD : django123
