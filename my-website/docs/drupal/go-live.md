---
sidebar_position: 2
---

# Go live checklist

## Pre-launch
- Remove the 401 from the site
- Disable these modules on live environments, Ideally these should have been set up in a config split to have been ignored.
  - Stage File proxy
  - Devel


## Post-launch
- Regenerate the XML sitemap with correct/upto date domain names. Check/set up different language versions if the site is Multilingual.
- Add the site to [StatusCake](https://www.statuscake.com/) for monitoring of uptime and SSL, with the following options.
  - Uptime monitoring
    - Check every 5 minutes.
    - Add to default contact group in alert settings.
    - Add hosting provider in the additional options section.
  - SSL
    - Check every 24 hours
    - Add to default contact group in alert settings

## Performance

## Security
