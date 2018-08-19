# DjangoAWS
Using AWS S3 to serve static files. 

To use the application, load environmet variable `AWS_ACCESS_KEY_ID`, `AWS_SECRET_ACCESS_KEY`, `AWS_STORAGE_BUCKET_NAME

Run `python manage.py collectstatic` 

This will load all your static files to s3 bucket and serve through view.py
