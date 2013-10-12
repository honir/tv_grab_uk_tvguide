tv_grab_uk_tvguide
-------------------

XMLTV grabber for the TV Guide website


RATIONALE
---------

Grabs TV guide schedules from the TV Guide website.  Intended as a fill-in for channels missing from the tv_grab_uk_rt XMLTV grabber.


OPERATION
---------

Drop-in module for the XMLTV package, run as a command-line script.  Output to a disc file in XMLTV format.


PRE-REQUISITES
--------------

Assumes you already have a working copy of "XMLTV".


COMPATABILITY
-------------

Tested with XMLTV 0.5.63, Perl v5.8.8 and Apache 2.2.3

(Tech note: many web hosts provide only 5.8.8 so no features are included which require a more recent version of Perl.)


LINKS
-----

The TV Guide website : http://http://tvguide.co.uk//

XMLTV DTD : http://xmltv.cvs.sourceforge.net/viewvc/xmltv/xmltv/xmltv.dtd

XMLTV : http://wiki.xmltv.org/index.php/Main_Page
