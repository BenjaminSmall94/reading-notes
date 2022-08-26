# Django Custom User Models

[Home](../index.md)

## Django Custom User Model

After starting a new Django Project you need to make an app called "accounts" and then start the local web server.

### AbstractUser vs AbstractBaseUser

AbstractBaseUser is much more complicated and customizable the AbstractUser, but much of its functionality is not necessary when learning the concepts.

### Custom User Model

Four steps are required to create a custom user model.

- update django settings
- create new CustomUser model
- create new UserCreation and UserChangeForm
- update the admin

Using a superuser is very useful when testing and building these apps. Then you should setup your templates views and urls to be able to interact with it.

> Now that our custom user model is configured you can easily and at any time add additional fields to it. See the [Django docs](https://docs.djangoproject.com/en/4.0/topics/auth/customizing/) for further instructions.

## DjangoX

Review [DjangoX](https://github.com/wsvincent/djangox) for me details

## Things I Want to Know More About

I want to see how this could be useful in the real word and see it in practice tomorrow! Always learning new things sharpens the brain!
