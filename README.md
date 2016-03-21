# phing-drush
Install Drush 5, 6, 7 and 8 with Phing.

# Usage
Create a config file ```build.properties``` having those properties:

```
# Where to install drush
drush.directory = /opt/drush

# Provide this to sync the directory accros different servers
aegir.user = aegir
aegir.host = localhost

# Optional, proxy configuration for downloading the files.
httpget.config.proxy = http://user:password@proxyhost:8012/
```

Once the config file is created and customized, run the command:

```phing -f build.xml```

# Todo
* You tell me

# Author
Pol Dellaiera

Contact: https://www.drupal.org/u/pol
