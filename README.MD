#Meteor Template

This is a work in progress. The idea is to have a template set-up with frequently used settings to get started with a Meteor app faster than I could if I were to use 'meteor create' and have to begin from there. This structure is expected to change and grow over time, and those modifications should flow here and be able to be tracked via git through this README.

##This Template includes the following additional Packages:

| Additional Packages     |
---------------------------
| less                    |
| iron:router             |
| meteorhacks:kadira      |
| meteorhacks:fast-render |
| nemo64:bootstrap        |
| meteorhacks:npm         |
| accounts-ui             |
| accounts-password       |

##The following folders have been added:

| Folders             |
-----------------------
| client              |
|   -views            |
|       -application  |
|       -includes     |
| collection          |
| lib                 |
| packages            |
| server              |

##Right now the the code in this 'app' is the default code from 'meteor create' restructured for this file strucure across the following files:

| Files                               |
---------------------------------------
|client/views/application/body.html   |
|client/views/application/header.html |
|client/views/includes/hello.html     |
|client/views/includes/hello.js       |
|client/views/main.js                 |
|collection/collections.js            |
|lib/router.js                        |
|server/server.js                     |
