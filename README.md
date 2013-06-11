Update: Since Version 0.16 you can configure the review tool from within
Okular.

okular-review-tool-mod
======================

Add magic markers with different colors to the review tool in Okular (KDE)

There is this awesome Review-Tool in Okular, that is unfortunately
lacking a bit configurability (though that appears to be on the wishlist).  I
think it could be an incredibly helpful study tool if it gets a bit more
polish.  Anyway, it can still be customized, and I'd like to give you a little
head start if you want to do that.

Installation
------------

Copy the icons to any location in `kde4-config --path icon`.  Most likely:

    cp icons/* ~/.kde/share/icons/

Find the locations of the `tools.xml` file from the Okular package in your
system, and copy the one from this repo there.  Take a look at that file (or
compare the two) and you'll surely get an idea how create one you like.
On my system the destination is here:

    cp -b tools.xml /usr/share/kde4/apps/okular/tools.xml

You get this
------------
There will now be several differently colored markers and ink tools and both
note tools.
