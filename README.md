PreSWLeuven
===========

Pre-Startup Week-end Leuven

# Setup the application

0. Present the big lines of Google AppEngine
1. Create appengine account:  https://appengine.google.com
2. Use the name for the app : \<PreSWLeuven>-\<Name>

# google appengine tools

1. appengine https://appengine.google.com/dashboard?app_id=s~paran-yo-staging
2. datastore index: https://appengine.google.com/datastore/indexes?&app_id=s~paran-yo-staging&version_id=2012-05-20.359049092030115504
3. datastore viewer: 
4. datastore statistics: https://appengine.google.com/datastore/statistics?&app_id=s~paran-yo-staging&version_id=2012-05-20.359049092030115504
5. application settings: https://appengine.google.com/settings?&app_id=s~paran-yo-staging&version_id=2012-05-20.359049092030115504

# Start to code

## App.yaml

1. what is a app.yaml https://developers.google.com/appengine/docs/python/config/appconfig
	2. STATIC: Static file handlers describe which files in the application directory are static files, and which URLs serve them.
  2. UPLOAD: This is necessary because the handler cannot determine which files in your application directory correspond with the given url and static_files patterns
  3. URL: The URL pattern, as a regular expression. 
  4. SCRIPT: A script handler runs a Python script in your application to determine the response for the given URL
  5. LIBRARIES: Specify that the application should use 3rd party library
  6. 

## helloworld.py

1. The model
  2. 
  

## NDB The database

* https://developers.google.com/appengine/docs/python/ndb/
* 
