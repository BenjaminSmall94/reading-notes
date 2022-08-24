# Django Crud and Forms

[Home](../index.md)

## Django Forms

Django provides a way to easily interact with forms to perform CRUD actions within a Django database.

> Forms are a flexible mechanism for collecting user input because there are suitable widgets for entering many different types of data, including text boxes, checkboxes, radio buttons, date pickers and so on. Forms are also a relatively secure way of sharing data with the server, as they allow us to send data in POST requests with cross-site request forgery protection.

The main steps Django does in form handling is:

1. Display the defaul form
2. Recieve data from a request and binds it to the form
3. Clean and validates data
4. Display error messages if data is invalid and promts the user to submit once more
5. Performs approrpriate action if data is valid.
6. Redirects user to another page.

### Declaring Forms

Declaring and building forms is very similar to declaring and using models and shares almost identical field types and many similar parameters.

Form field include but are not limited to:

> BooleanField, CharField, ChoiceField, TypedChoiceField, DateField, DateTimeField, DecimalField, DurationField, EmailField, FileField, FilePathField, FloatField, ImageField, IntegerField, GenericIPAddressField, MultipleChoiceField, TypedMultipleChoiceField, NullBooleanField, RegexField, SlugField, TimeField, URLField, UUIDField, ComboField, MultiValueField, SplitDateTimeField, ModelMultipleChoiceField, ModelChoiceField.

Paramters include but are not limited to:

- required
- label
- label_suffix
- initial
- widget
- help_text
- error_message
- validation
- localize
- diabled

Django provides coutless other ways to interact with forms and data from forms in order to build effective CRUD applications. But for that you will just have to tune in next time! For tonight, CPT Small is signing off!

## Things I Want to Know More About

Like always, I want to see these Django forms in action so that I can get hands on experience implementing them in a powerful and helpful application.
