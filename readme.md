This is a Boilerplate template for quickly starting a django project.

Features :

- The project is named as 'base'.
- The configuration is available in sqlite3/pgsql backends.
- The apps directory has been initialized, to keep apps handy.
- Rest Framework is added to installed apps.
- Defined STATIC_ROOT, MEDIA_ROOT and STATICFILES_DIRS.
- URL Configuration is done for serving media files.
- On development server, the static files will be served no extra config needed.
- To use this on production, add a URL mapping for STATIC_ROOT
  then run python manage.py collectstatic
- The templates directory has been initialized, and base templates are created.
- A Homepage is created, which is linked to base.js and base.css, 
    I've put background colour and an alert as a verification step.
- I am from India, so the timezone is set to 'Asia/Kolkata'.
- Also, take note that this project follows the PEP-8 standards
    It uses Black as the formatter, autoPEP8, and flake8 as linter.
- Also, the pillow library has been added because of how commonly used it is.


** BONUS ** (FOR VSCODE USERS)
- I've included my settings.json
    - Please modify the python path to your correct path


- I've Also Included a PWA Library
    Add the following to settings.py with correct values to activate it
    # PWA SETTINGS
    PWA_APP_NAME = 'Your PWA'
    PWA_APP_DESCRIPTION = "Your Description"
    PWA_APP_THEME_COLOR = 'some color'
    PWA_APP_BACKGROUND_COLOR = 'some color'
    PWA_APP_DISPLAY = 'standalone'
    PWA_APP_SCOPE = '/'
    PWA_APP_ORIENTATION = 'any'
    PWA_APP_START_URL = '/'
    PWA_APP_STATUS_BAR_COLOR = 'default'
    PWA_APP_ICONS = [
        {
            'src': 'some icon',
            'sizes': '160x160'
        }
    ]
    PWA_APP_ICONS_APPLE = [
        {
            'src': 'some icon',
            'sizes': '160x160'
        }
    ]
    PWA_X = '(device-width: 320px) and (device-height: 568px)'
    PWA_Y = 'and (-webkit-device-pixel-ratio: 2)'

    PWA_APP_SPLASH_SCREEN = [
        {
            'src': 'some icon',
            'media': PWA_X + PWA_Y
        }
    ]
    PWA_APP_DIR = 'ltr'
    PWA_APP_LANG = 'en-US'