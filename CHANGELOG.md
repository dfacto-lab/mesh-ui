# MeshAdminUI Changelog

## Version 0.7.2 (in progress)
* Date fields now work with ISO 8601 strings rather than unix timestamps
* Fix bugs with lists of microschemas (SUP-4712)

## Version 0.7.1 (2017-07-07)
* Synchronize version with maven

## Version 0.6.7 (2017-07-06)
* Fix adding node to node list
* Change downloaded thumbnail width to 200

## Version 0.6.6 (2017-06-20)
* Replace version references with simple strings (fix for mesh update)

## Version 0.6.5 (2017-06-08)
* Fix image upload when updating nodes

## Version 0.6.4 (2017-05-22)

#### Fixes
* Schema & Microschema description is no longer a required field

## Version 0.6.3 (2017-05-16)

#### Fixes
* Send a header to prevent being logged in as anonymous user

## Version 0.6.2 (2017-05-08)

#### Features
* Microschemas can now be assigned to projects
* Descriptions can now be assigned to schemas & microschemas

#### Fixes
* Remove the "binary" option from micronode editor

## Version 0.6.1 (2017-04-13)

#### Fixes
* Fix project creation
* Fix error when attempting to translate a node
* Fix incorrect search query
* Display error when attempting to publish a node with an unpublished ancestor

## Version 0.6.0 (2017-03-15)

#### Features
* Updated to work with latest Mesh APIs as of Mesh **v0.8.x**
* Add paging to nodeSelector dialog
* Add list/grid view toggle to nodeSelector dialog
* Automatically logs user out when session has expired
* Simple draft/published handling
* Numerous styling improvements