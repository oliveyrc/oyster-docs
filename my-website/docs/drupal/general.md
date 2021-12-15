---
sidebar_position: 1
---

# General setup
All new Drupal sites need to follow the following conventions,

## Initial setup

### Username/password
  - Username - webteam
  - Password - 20 characters alphanumeric, a useful resource for generating random passwords http://privacycanada.net/strong-password-generator/
  - Store these details in the oyster.kdb file in the keypass folder on Google Drive.
  
### Drupal configuration
- Disable the following modules/themes/content types, these will be removed at a later stage with an updated Oyster
  install profile,
    - Article Content type
    - Tour module
    - Quick edit module
    - Shortcuts module
    - Comments module
    - Bartik theme

### General 
 - If there are view print friendly and/or download PDF links make sure to add ref=”noindex"
