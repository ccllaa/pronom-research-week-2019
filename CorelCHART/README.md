# CorelCHART Document file format

.CCH

CorelCHART Documents are vector graphics of charts, tables, etc. Software was bundled with CorelDRAW from 1992 to 1994.

CorelCHART version 3 & version 4 files have the same header while version 5 has its own unique header.

.CCH files begin with the TIFF file format header, but contain no TIFF image data. 

Version 3 & 4 files begin with the TIFF header, have 4 variable bytes, then have 16 unique bytes, in ascii they are "3DF.0002 04dec91"
Version 5 files also begin with the TIFF header, have 4 variable bytes, then also have 16 unique bytes, in ascii they are "CorelCHART V5.0 "


Format Name: CorelCHART document
Versions: 3 & 5
PUID:  x-fmt/310 but new PUID needed to distinguish version 3&4 from 5
Extension: CCH
MIME: Unknown
Description: CorelCHART Documents are vector graphics of charts, tables, etc. Software was bundled with CorelDRAW from 1992 to 1994.
Format Type: Image (Vector)
Vendor: Corel Corporation
 

