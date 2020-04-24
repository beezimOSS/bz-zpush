# bz-zpush

This project will handle the integration of zpush in custom builds

We will try to make it as clear as possible and take notes for other projects to make other integrations easy.

Identified steps: 

* Integrate Zpush code
* Integrate Zimbra backend
* Integrate Zimbra backend Configuration to zmconfigd and/or zmlocalconfig
* Configure logs and log rotate
* Integrate in store deployment

Features : 

* Check zimbra LDAP for Mobile access


Architecture v1: 

* Use the spell apache

Architecture v2: 

* provide a phpfpm container (need to define the container architecture)
