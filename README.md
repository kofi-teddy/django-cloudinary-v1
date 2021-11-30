# django-cloudinary-v1

Basic django cloudinary configurations

This helps to store media files with cloudinary

### Steps 
1. setup django projects
2. install django-cloudinary-storage
3. import cloudinary_storage in settings 
4. Add to settings
    INSTALLED_APPS = [
    # ...
    'django.contrib.staticfiles',
    'cloudinary_storage',
    'cloudinary',
    # ...
    ]
5. Add to settings 
    DEFAULT_FILE_STORAGE = 'cloudinary_storage.storage.MediaCloudinaryStorage'
