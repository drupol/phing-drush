# phing-drush
Install Drush5, 6 and 7 with Phing

# Usage
Create a file 'build.properties' having those properties:

```
# Where to install drush
drush.directory = /opt/drush

# Provide this to sync the directory accros different servers
aegir.user = aegir
aegir.host = localhost

# Optional, proxy configuration for downloading the files.
httpget.config.proxy = http://user:password@proxyhost:8012/
```

# Todo
* You tell me

# Author
Pol Dellaiera
Contact: https://www.drupal.org/u/pol