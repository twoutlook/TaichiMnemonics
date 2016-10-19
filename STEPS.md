
# Create a new Github project
  including .gitignore with Java, so far
  LICENSE
  README.md

# Create a new C9 project
  clone Github project
  
# Edit .gitignore
  Follow DjangoGirls' guideline
  https://tutorial.djangogirls.org/en/deploy/
 
# Install python3.5 and python3.5-venv
    sudo apt-get install python3.5 python3.5-venv -y

# Create virtual environment
    python3.5 -m venv myvenv

# Activate virtual environment
    twoutlook:~/workspace (master) $ source myvenv/bin/activate
    (myvenv) twoutlook:~/workspace (master) $ 
    
# Upgrade pip
    pip freeze
    pip install --upgrade pip
    
# Install Django
    pip install django
    
 
# Create a new Django project    
   django-admin startproject mysite 
    
# Create a new project appplication app001
    cd mysite   
    python manage.py startapp app001
    
# Create a DB script
    python manage.py makemirgrations
    python manage.py migrate
    
# Sync DB
    source db.py
    
# Create a superuser
    source db.py
    
# Create script of run development server
    python manage.py runserver $IP:$PORT
    
# Visit mysite and admin    
    https://taichi-mnemonics-twoutlook.c9users.io/    
    https://taichi-mnemonics-twoutlook.c9users.io/admin  
    
    
# Run development server
    source db.py
    
# New terminal and activate virtual environment
    source myvenv/bin/activate
   
# Git and Github
    git add.
    git status
    
    // When something is wrong, before commit, to reset
    git reset

    
    
    
    
    



    