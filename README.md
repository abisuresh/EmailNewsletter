# EmailNewsletter
Email Newsletter using Django and Twilio SendGrid based on tutorial here: https://www.twilio.com/blog/build-email-newsletter-django-twilio-sendgrid

How to run: 

* Git clone project 
* Run the following command at the root directory of this project: python manage.py runserver
* Development server running at http://127.0.0.1:8000/ by default  

* Create, confirm and delete are actions that are implemented. 
* Confirm and delete require email and conf_num query parameters 

To setup admin user:

python manage.py createsuperuser
