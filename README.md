- pip3 install 'django<4'
- django-admin startproject pixu .
- pip install django-cloudinary-storage==0.3.0
- pip install Pillow==8.2.0
- pip freeze > requirements.txt
- pip install djangorestframework
- pip install django-filter
- pip install dj-rest-auth==2.1.9

- pip install 'dj-rest-auth[with_social]'  <----- NOT THIS  #  BUT THIS ------>  pip install dj-rest-auth[with_social]

- pip install djangorestframework-simplejwt==4.7.2
-  **Pagination**
- JASON Web token 
- python3 manage.py createsuperuser

- ### python manage.py startapp (and name of the app)
- python3 manage.py makemigrations
- python3 manage.py manage.py migrate
## Post view tests
  - user can list all the posts
  - logged in user xan create a post
  - logged out user cant create a post

## PostDetail view tests
  - user can retrieve a post with a valid id
  - user cant retrieve a post with an invalid id(404)
  - user can update the posts they own
  - user cant update the posts they dont own
   