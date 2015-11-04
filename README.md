libps4-std-include
=====

> Imported by libps4-generator to generate libps4

# Description

This is a link-less mirror of /usr/include of an amd64 FreeBSD 9.0 RELEASE.

##TODO
- Find the most suitable headers (9.3?) which expose the capabilities of libScelibCInternal.sprx the best. E.g. not all of C11 is exposed as part of the current 9.0 headers.
- Trim headers which hold no intrinsic value (expose only non-existing symbols - no other header functionality)
