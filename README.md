# Provus-Local
Docksal based starter kit for local development of 
Provus sites and Provus project work.

## Local Dev Setup
The following insctuctions assume you have already cloned this
provus-local repo into a certain directory name of your choosing.
Go into that directory to do all the following commands.  Do not 
change directories unless it tells you to in a step.

### Local Dev for new Provus based site
```
fin init
```

### Local Dev for Drupal.org Development on Provus project
```
git clone git@git.drupal.org:project/provus.git site
fin init drupal-org-dev
```

### Boom! Provus is installed.  
It should provide a url and uli to login at end of initialization.


## Development Commands

### Drush
```
cd site
fin drush ...
```
All fin drush commands should happen within your site directory.

### Build Theme
```
fin build-theme [name_of_theme]
Example:
fin build-theme provus_bootstrap
```
This assumes that this custom theme will live inside of 
site/web/themes/custom/ directory.