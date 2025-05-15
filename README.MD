## Laravel Herd Command


### Start Running herd on project
``cd ./projectname``

``herd link``

### Stop Running herd on project
``cd ./projectname``

``herd unlink projectname``

### Start running https/ssl on project
``cd ./projectname``

``herd secure``

### Stop running https/ssl on project
``cd ./projectname``

``herd unsecure``

### Check list https
``herd secured``

## Herd sharing to public url
``herd share`` or ``herd share projectname.test``

## Herd sharing to public url using ngrok
``ngrok http --host-header=rewrite unsecured-site.test`` 

or

``ngrok http --host-header=rewrite secured-site.test:443``
