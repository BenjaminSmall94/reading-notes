# Django Models

[Home](../index.md)

## Using Models

Django uses python objects as models for data. These models define the structure of data along with often times the default value, maximum size, field types etc. After you havbe models, Django does all the heavy lifting of communicating with the database.

When designing models you should make models for every data set of similarly grouped data (a group of related information). Once models are designed you have to define relationships between models, one to one (OneToOneField), one to many (ForeignKey) and many to many (ManyToManyField).

Models also have fields to help structure data. Among these fields are many common field arguments such as default, help_text, choices, primary key, and others! You may have to define locallibrary models in order to use them. At this point you might have to re-reun database migrations to make sure your edits are applied.

## Django Admin

Before using the admin function you might want to register models.

> Register the models by copying the following text into the bottom of the file. This code imports the models and then calls admin.site.register to register each of them.

```python
from .models import Author, Genre, Book, BookInstance

admin.site.register(Book)
admin.site.register(Author)
admin.site.register(Genre)
admin.site.register(BookInstance)
```

This admin functionality allows you to build a superuser with many advanced abilities to help administrate a website and access advanced configuration. Then finally you can configure list views.

## Things I Want to Know More About

I want to practice implementing Django for supporting Databases. I am also curious to use actual SQL as well but I believe that is a later module.
