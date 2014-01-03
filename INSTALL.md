Installing
==========

* This initial build ONLY works on NIOS grids running 6.8.1 or later.

    There is a vague chance you can get to work from a whitebox or
your desktop, but there are a number of hoops you have to jump through to
get past XSS and self signed cert issues that Im not prepared to deal
with on this beta release.

    Just install the sucka and try it out first.

    *You also MUST* install this on a grid so that you can force your browser
to accept your self signed cert that lurks on 90% of infoblox grids.

    (and, if you dont have admin access to your grid, you probably shouldnt
be messing with this beta anyway)

*TO install*

* Enable HTTP file distribution on the Grid master

* Upload the .tgz file to the file distribution and make sure you check
the box [x] unpack the tar file

* Go to https://\(yourGM.\)/snapins/nimob

wait for it to load, see what happens

### Saving a webapp on IOS devices.

You *can* add this as a homescreen link in IOS, and it should work, but
Im seeing some oddnesses with some of the css. It may work, it may not
