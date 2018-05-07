Drupal Installation profile scripts
===================================

Some useful scripts for working with Drupal installation profiles

# Scripts
- **build.sh**: Creates a new installation of the profile.
- **create_features.sh**: Exports all the configuration to features. It will update the features if they already exist.
- **contrib_download.sh**: Downloads all the contrib modules and applies the patches. Is just an alias for drush make --no-core --allow-override --contrib-destination=. drupal-org.make -y
- **project_update.sh**: Updates the code, downloads the contrib code, updates the DB, reverts the features and cleares the cache. It doesn’t do a full rebuild.

# Credits
All scripts are based on the [profile skeleton scripts](https://github.com/DavidHernandez/profile-boilerplate/tree/master/profile/scripts) used on [Profile Boilerplate](https://github.com/DavidHernandez/profile-boilerplate) project, created by [DavidHernandez](https://github.com/DavidHernandez).