# Guides
1. Create Project
 `django-admin startproject core`

 2. Create App
 `django-admin startapp shop`

 3. Add app to settings.py, INSTALLED APP
 `'shop.apps.ShopConfig'`

 4. Installed Pillow ( use to manipulate images in python )
 `pip install Pillow==7.0.0`

 5. Create Shop Models and migrate
 `python manage.py makemigrations`
 `python manage.py migrate`

 6. Register Models in admin.py

 7. Create superuser and runserver
 `python manage.py createsuperuser`
 `python manage.py runserver`

 8. Add products/items to the shop via admin interface

 9. Create Products Views

 10. Create urls.py and register Urls in main urls.py

 11. Create templates directory and register it in the settings.py

 12. Create template files accordingly

 13. Using the development to serve media file, we define were django should
 get the media files in the settings.py and urls.py

