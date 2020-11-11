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

'NAME': 'bbq',
'USER': 'matt',
'PASSWORD': 'BBQ',

brew install postresql ---- will need to install postgres on VPS
Remember that database is BBQ
psql BBQ
CREATE EXTENSION pg_trgm;
*Needed for trigramsimilarity*
*Make sure to update code to include trigramsimilarity search Page 89*

git remote add origin git@github.com:mgroff38/bbq.git
git pull https://github.com/mgroff38/bbq.git
git reset --hard

pip freeze > requirements.txt - Use to build requirements.txt
pip install -r requirements.txt

## Usage/Ack

Catering Template from W3 Schools. 
