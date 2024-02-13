# Django Upload

## Setup

```shell
python3.12 -m venv venv
source ./venv/bin/activate
```

## Running

```shell
git clone https://github.com/jkeam/djangoupload
cd djangoupload
cp env.template .env  # update .env with real values
pip install -r ./requirements.txt
python ./manage.py migrate
python manage.py runserver
```

## Using
1. Use `http://localhost:8000/post/` to upload image
2. Use `http://localhost:8000/` to view image

## References
1. [Upload tutorial](https://learndjango.com/tutorials/django-file-and-image-uploads-tutorial)
2. [Django Storage](https://django-storages.readthedocs.io/en/latest/backends/amazon-S3.html)
