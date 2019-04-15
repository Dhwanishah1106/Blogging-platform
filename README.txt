FEATURES :
- create a blog
- edit a blog
- delete  Blog
- comment on blogs
- approve and disapprove comments
- view published blogs
- view unpublished blogs
- search and filter in the list of blogs (admin)

Environment setup
python3 -m venv myvenv

. myvenv/bin/activate

Install Dependencies

pip install -r requirements.txt
Set Database (Make Sure you are in directory same as manage.py)

python manage.py makemigrations
python manage.py migrate

Create SuperUser
python manage.py createsuperuser
After all these steps , you can start testing and developing this project.

To run on localhost
python manage.py runserver
