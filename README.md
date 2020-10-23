# Python Graphene

```shell script
django-admin startproject app
python manage.py migrate
python manage.py startapp tracks
python manage.py makemigrations
python manage.py migrate

```

```shell script
python manage.py shell

>> from tracks.models import Track
>>> Track.objects.create(title='Track 1', description='Track 1 description', url='https://track1.com')
<Track: Track object (1)>
```