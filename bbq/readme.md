# bbqsite
This is the readme document for the BBQSITE project
Author Matthew Groff


## Issues
-Need to investigate setup of email sending with gmail.
-Remember that HTML and CSS is custom, need to ensure that it is not overwritten when troubleshooting from book code. 


## Reference
https://www.digitalocean.com/community/tutorials/how-to-set-up-django-with-postgres-nginx-and-gunicorn-on-ubuntu-20-04
source env/bbq/bin/activate
pip install django
pip install django_taggit==1.2.0
pip install markdown==3.2.1
pip install psycopg2-binary==2.8.4
pip install django-crispy-forms
pip install Pillow
pip install social-auth-app-django==3.1.0
pip install django-extensions==2.2.5
pip install werkzeug==0.16.0
pip install pyOpenSSL==19.0.0
pip install celery==4.4.2
apt-get install rabbitmq
pip install flower==0.9.3
pip install braintree==3.59.0
pip install WeasyPrint==51
pip install -U python-dotenv


brew install postresql ---- will need to install postgres on VPS

git remote add origin git@github.com:mgroff38/bbq.git

git pull https://github.com/mgroff38/bbq.git

git add -A - do this everytime you want to push to github
git commit -m "some sensible and descriptive commit message describing why the codebase has changed" - do this everytime you want to push to github
git remote add origin https://github.com/<your-account>/<your-repo>.git - only needed once
git push -u origin master - do this everytime you want to push to github
git reset --hard

pip freeze > requirements.txt - Use to build requirements.txt
pip install -r requirements.txt

## Usage/Ack

Catering Template from W3 Schools. 
