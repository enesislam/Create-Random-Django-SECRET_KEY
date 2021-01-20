# Create-Random-Django-SECRET_KEY
How to create a SECRET_KEY for settings.py

>>> from django.utils.crypto import get_random_string
>>> chars = 'abcdefghijklmnopqrstuvwxyz0123456789!@#$%^&*(-_=+)'
>>> SECRET_KEY = get_random_string(50, chars)
>>> print SECRET_KEY

.........
Cause of share: 
File "C:\Users\User\Desktop\Project\Env\lib\site-packages\environ\environ.py", line 277, in get_value
    raise ImproperlyConfigured(error_msg)
django.core.exceptions.ImproperlyConfigured: Set the SECRET_KEY environment variable

