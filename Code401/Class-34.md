# API Deployment

[Home](../index.md)

## Django Setting Best Practices

Different environments such as dev vs production will have different settings for different purposes. Generally dev environments will have more verbose output. Additionally sensistive data needs to be hidden from the public and not tracked as part of your version control system.

### Different Approaches to tracking settings across environments

- `settings_local.py`

   This a very common and oldest method to track django settings. The main benefit is that this file will not be tracked by git. But the downside is you'll have to share this file among developers.

- Separate Settings for each environment

   The pros is that the settings are in VCS and can be easily shared but the downside is you'll have to cmoe up with a different way to protect secret information.

- Environmental Variables (OS Moduel)

   Python's OS module provides functionality for using evnironmental variables for keeping your secret data secret. There is barely any downside except you just need to account for sharing the environmental configuations between developers.

- django-environ

   This application takes care of everything for you, use this one.

### SSH: Encryption, Ports, and Connection

SSH, Secure Shell Protocol, (don't ask me where the H comes from) is a remote administration protocol that lets them take control of there server remotely over the internet. It succeeded the unencrypted system of Telnet and provides mechanisms for authenticating a remote user, and transferring inputs from cthe client to the host.

In Macs or Linux it's as simple as  `ssh {user}@{host}`

The three types of encryption used are symmetrical, asymmetrical, and hasing.

## Things I Want to Know More About

I want to learn about using SSH in building secure full stack applications that are prodcution quality.
