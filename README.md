macfocus
--------

  macfocus moves the current window focus to a specified application.

  Usage:
     
    macfocus <application_name>

  Examples:
  
    $ macfocus chrome
    $ macfocus Emacs
    $ macfocus 'Google Chrome'

macsendstring
------------

  sends a string to a specified application and bring the focus back to the
  calling application.

  Usage:
  
    macsendstring <application_name> <string_to_send>

  Examples:
  
    $ macsendstring chrome 'hello, world'
    $ macsendstring iTerm 'echo "hello, world"'

macpasteto
----------

  pastes the clipboard content to a specified application.

  Usage:
  
    macpasteto <application_name>

  Examples:
  
    $ macpasteto chrome
    $ macpasteto iTerm
    $ macpasteto 'Google Chrome'
