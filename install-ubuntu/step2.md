Now that the repository is configured, we need to install the package signing
key to allow automatic verification of the source and integrity of the packages
that will be downloaded.

`wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add -`{{execute}}

Now, update the package indexes:

`sudo apt-get update`{{execute}}
