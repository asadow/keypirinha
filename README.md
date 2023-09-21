# keypirinha
My Keypirinha Settings

## Configure Package: FilesCatalog:

```
# Things can be any name.
[profile/Things]
# Activate this profile?
activate = yes
# What are the paths?
# Note: ** signals recursive scanning, but does not include folders directly beneath the path.
# We repeat paths with and without \** so folders one level beneath the path are included.
# SKYDRIVE refers to OneDrive.
paths = 
    ${var:KNOWNFOLDER_PROFILE}\repo
    ${var:KNOWNFOLDER_PROFILE}\repo\**
    ${var:KNOWNFOLDER_SKYDRIVE}
    ${var:KNOWNFOLDER_SKYDRIVE}\**
    ${var:KNOWNFOLDER_DOWNLOADS}\**
    ${var:KNOWNFOLDER_SCREENSHOTS}\**
# How many folders deep for recursive scanning?
max_depth = 3
# Include folders in search results?
include_dirs = yes
```

## Configure Package: Bookmarks

```
[provider/Chrome]
# Should bookmarks from the Chrome browser be referenced?
# Default: yes
enable = no

[provider/Firefox]
# Should bookmarks from the Chrome browser be referenced?
# Default: yes
enable = no
```
