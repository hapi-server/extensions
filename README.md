# extensions
The HAPI server has always supported extensions that can be safely ignored.  For example, in 
a server response x_plot might be a URL that generates a plot of the data.  This is not part of the
HAPI specification, but this is allowed since it starts with x_.  

This repository is intended to allow groups to share extensions they have made.  It's likely multiple groups
will have similar goals, and this ticket may allow them to share ideas and so things in a similar way.  Here we 
try to describe first how one documents an extension, so that clients or servers might use
it, and second, descriptions of extensions themselves.

See tickets for discussions of new extentions.  Mature extensions should be described using documents linked to from here.

# Example extensions
## Availability
How does one know when data can be requested?

## Data Reduction
This allows one to request reduced versions of the data.

# Catalog of Extensions

| Identifier   |  Title  | Curator | Description |
|----------|:-------------|:------|:---|
| x_colorLookup | identifies colors for string data | Jeremy Faden | https://github.com/hapi-server/extensions/issues/2 |
| x_customRequestOptions | simple parameters for server | Sandy Antunes | https://github.com/hapi-server/extensions/issues/1 |
| x_relations | identifies courser resolutions of the data | Eelco Doornbos | https://github.com/hapi-server/extensions/issues/3 |
| x_latitude, x_longitude | identifies the Earth surface location of the station where data is read |  | https://github.com/hapi-server/extensions/issues/4 |
| write | Ability of server to accept data through API | Jeremy Faden | |

