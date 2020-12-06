# portfolioDjangoApp
my practice portfolio app from https://realpython.com/

[1]

Model defines the data structure. This is usually a database and is the base layer to an application.

View displays some or all of the data to the user with HTML and CSS.

Controller handles how the database and the view interact.

[2]

If you want to learn more about the MVC pattern, then check out Model-View-Controller (MVC) Explained – With Legos.

In Django, the architecture is slightly different. Although based upon the MVC pattern, Django handles the controller 

part itself. There’s no need to define how the database and views interact. It’s all done for you!

[3]

The pattern Django utilizes is called the Model-View-Template (MVT) pattern. The view and template in the MVT pattern 

make up the view in the MVC pattern. All you need to do is add some URL configurations to map the views to, and Django 

handles the rest!

[4] To start a virtual environment in cmd

python3 -m venv venv

source venv/bin/activate

[5]To start an app

python manage.py startapp <app name>

Ex: python manage.py startapp projects

[6] To create a database and data

 python manage.py makemigrations <app name>
 
 python manage.py migrate <app name>
  
 Ex:  python manage.py makemigrations projects

  python manage.py migrate projects 


[7] To start a shell

python manage.py shell

To exit from the shell

Ex: exit

[8] to create super user

ex: python manage.py createsuperuser





