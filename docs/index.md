# introduction

- Backend : [![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)](https://www.djangoproject.com/) [![ninja](https://yongbeomkim.github.io/assets/code/ninja.png)](https://django-ninja.rest-framework.com/)

- Frontend : [![TypeScript](https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/) [![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)](https://ko.reactjs.org/)


## Author

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.


<figure class="align-center">
  <img src="{{site.baseurl}}/assets/django/map.png">
  <figcaption>django map</figcaption>
</figure>

## Project layout

    .gitignore   # The configuration file.
    django/      # backend
    react/       # frontend
    media/       # media files

    django/

        # Django settings.
        mysite/   # The documentation homepage.
            staticfiles/
                __init__.py
                apps.py
            settings.py
            urls.py

        # User Model Customize & Ninja Base API
        core/
            templates/
                base.html
                index.html
            admin.py
            api.py
            models.py
            router.py                
            schema.py
            tests.py
            urls.py
            views.py

        # API contents
        content/   
            router.py                
            schema.py
            admin.py
            models.py
            tests.py
            views.py            
