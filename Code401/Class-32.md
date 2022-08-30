# Django and Docker

[Home](../index.md)

## Permissions and Postgresqul

### Permissions

After a user is identified and authenticated, they have to be authorized in order to be proceed and access data or code. This is what permissions is for. This is especially important with APIs.

### How Permissions are Determined

In REST frameworks permissions are defined in a permissions class. Also you can get more specific and allow object level permissions if you'd like certain users to be able to perform CRUD operations on only part of the site but not others.

### Commmon permissions

- `AllowAny`
- `IsAuthenticated`
- `IsAdminUser`
- `IsAuthenticatedOrReadOnly`

Additionally you can set custom permissions

### Overview

The following table lists the access restriction methods and the level of control they offer over which actions.

> | | queryset | permission_classes | serializer_class |
> | --- | --- | --- | --- |
> | Action: list | global | global | object-level* |
> | Action: create | no | global | object-level
> | Action: retrieve | global | object-level | object-level
> | Action: update | global | object-level | object-level
> | Action: partial_update | global | object-level | object-level
> | Action: destroy | global | object-level | no
> | Can reference action in decision | no** | yes | no**
> | Can reference request in decision | no** | yes | yes

## Things I Want to Know More About

I want to get some practice using SQL and see how it can help me build awesome databases!
