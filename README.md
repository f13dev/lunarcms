# Lunar CMS 3

Lunar CMS is an open source PHP & MySQL based content management system designed for use on web servers.

This software is released under the 2-Clause (simplified) BSD license

Lunar CMS 3.3-3 is the final release of Lunar CMS version 3, work is now commencing on Lunar CMS v4

## Changelog

### Lunar CMS 3.3-3
* Additional security added to administration forms to eliminate CSRF attacks.
* Additional security added to contact_form.ext.php to eliminate CSRF usage.
* Modification of ELFinder connector.php to eliminate CSRF usage. PHP files can no longer be uploaded for additional security along with the removal of the rename function.

### Lunar CMS 3.3-1
* Added code to ensure the elfinder connector can only be accessed by the 'Super User' or an 'Admin' due to a security vulnerability.

### Lunar CMS 3.3
* Modified pages_edit to update the homepage setting if required
* Modified the menu generation code to fall back to alphabetic order if multiple pages share the same sort order
* Added autofocus to the login email address field
* Modified the add user & edit user page with stricter validation
* Including the admin head and foot within the user delete page to ensure users are logged in before access

### Lunar CMS 3.2
* Solving an error with the Captcha image creator
* Changed the user management section to allow the 'super user' to change their password
* Changed the front end 'My Account' page to allow users to update their details

### Lunar CMS 3.1
* Cleaning up code and closing database connections when finished with.
