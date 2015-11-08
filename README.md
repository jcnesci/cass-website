# cass-website

Cass' website.

## Login

* u: cass' first and middle names together, lowercase
* pw: cass middle + my smallest soccer number (zero-prepended)

## Moving it from Cass' localhost to mine

Followed [these instructions](https://managewp.com/how-to-create-a-local-copy-of-a-live-wordpress-site), it worked. Details to add:
  * before importing the DB in my phpMyAdmin, I had to create a new DB (named it the same as the old one, as seen in wp-config, 'DBWPress').
  * the links to the pages were broken at first, I fixed it by going into the Admin panel, resetting the permalinks to default, then setting them back to what it was (ie. the 2nd option).