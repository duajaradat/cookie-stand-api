# API Deployment

## Author :

Du'a Jaradat

## Collaborators:

*Haneen*
*Tasneem*
*Mona*
*Tahny*

---

## Links and Resources

- [Pull Request](https://github.com/duajaradat/cookie-stand-api/pull/1)

---

## Overview

First steps are to make sure your Application is able to run well in a remote environment.

---
## Feature Tasks and Requirements

**Use API Quick Start Template**

 - Create a new repo cookie-stand-api that uses [API Quick Start](https://github.com/codefellows/python-401-api-quickstart) as a template.

 - Modify your application using instructions in README.md found in root of repo.

         - Change things app folder to be cookie_stands
         - Go through code base looking for Thing,thing and things change to cookie-stand related names.
         - E.g. Thing model becomes CookieStand
         - E.g. ThingList becomes CookieStandList
 - Pro Tip: Do a global text search looking for thing

         -  Search should be case insensitive.

**Deeper CookieStand Changes**

 -  The CookieStand model must contain

 **Notice the use of JSONField which is a newer feature introduced in Django 3.1.

**Database Deployment Requirements**

 - Host your Database at [ElephantSQL](https://www.elephantsql.com/)

**Site Deployment Requirements**

 - Deploy Docker container to Heroku


 ---

## Implementation Notes

 - Site must use environment variables.

---

## Useful Terminal Commands

 - `docker-compose up --build`
 - `docker-compose down`
 - `docker-compose restart`
 - `docker-compose run web python manage.py migrate`
 - `docker-compose run web python manage.py collectstatic`


---

## User Acceptance Tests

 - Manually confirm API using API Tester, Postman or HTTPie

          -  Remember to use deployed url, not localhost

---

## Tools and Dependencies

- Poetry
- flake8
- black
- django

---

