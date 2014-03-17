shout
=====

Shout - Command-Line Push Notifications

This miniscule script uses the Prowl notification service to send push
notifications to an iOS device. It is designed for notifying
programmers when long-running compilation jobs or similar tasks have
completed.

You need a Prowl API key to use this script:

http://www.prowlapp.com/

Set the environment variable PROWL_API to your key, then run the
script like this:

shout make

The last 1024 bytes of output from the make command, along with
success/failure will be reported in the push notification.

You can also run shout with no arguments, in this case it will send a
minimal push notification.

