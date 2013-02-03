[odder2014.dk](http://odder2014.dk)
==

Instructions on how to build the site from Drupal 7.

Requirements
--

* [drush](http://drupal.org/project/drush)

Installation
--

    drush make soc_odder.build ~/workspace/soc_odder_build
    
Create the settings.php in sites/default and chmod 755
Create "files" directory in sites/default and chmod 755

Navigate to the root directory in a webbrowser and run the "minimal" install profile.

Enable the "soc_odder" module.

    drush en soc_odder