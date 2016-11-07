# Users

## User Object

### Attributes

Attribute         | Type    | Description
------------------|---------|------------
description       | string  | About text, visible on the public profile
email             | string  | Used for notifications and might be visible on career site
facebook-profile  | string  | URL to Facebook profile
google-profile    | string  | URL to Google+ profile
hide-email        | boolean | `true` if e-mail address should be hidden on career site
instagram-profile | string  | URL to Instagram profile
linkedin-profile  | string  | URL to LinkedIn profile
name              | string  | The user's name
other-profile     | string  | URL to other profile
phone             | string  | Phone number
picture           | object  | Picture object (Profile picture)
role              | string  | Permission role (`no_access`, `user`, `recruiter` or `admin`)
title             | string  | Title, e.g 'CEO' or 'Account manager'
twitter-profile   | string  | URL to Twitter profile
username          | string  | Internal username, used in mentions
visible           | boolean | `true` if profile is visible on the career site

### Relations

Relation   | Description
-----------|------------
department | Listed under this department on the career site
location   | Listed under this location on the career site
