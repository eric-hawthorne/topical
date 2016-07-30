README.txt

How to initialize topicality.net server

1. Start the webapp. On topicality.net server:
screen
cd /opt/topical/relish/artifacts
relish -web 8081 everybitcounts.net2006/topical/ >& relish.log
# Ensure it stays running - does not return to prompt
Ctl-a d    # detach from the screen, backgrounding it.

In browser, browse to http://topicality.net/setMasterPassword
# Enter blank for old master passord, and create a master password
# for administering topicality.net webapp.
# Do not forget this password.

In browser, browse to http://topicality.net/setSignupPassword
# Enter the master password and create a user signup password.

# The current values for these are in the usual place.

Browse to http://topicality.net

Create a user account by entering user name and user creation password.
Create the actual password for the account.

Browse to http://topicality.net/importOntology