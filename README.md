# keypirinha
My Keypirinha Settings

## Configure Package: FilesCatalog:

[profile/Things]
activate = yes
paths = 
### ** does not catch folders 1 level deep inside the path
### so paths are repeated with and without suffix: \**
    ${var:KNOWNFOLDER_PROFILE}\repo
    ${var:KNOWNFOLDER_PROFILE}\repo\**
    ${var:KNOWNFOLDER_SKYDRIVE}
    ${var:KNOWNFOLDER_SKYDRIVE}\**
    ${var:KNOWNFOLDER_DOWNLOADS}\**
    ${var:KNOWNFOLDER_SCREENSHOTS}\**
max_depth = 3
include_dirs = yes

## Configure Package: Bookmarks

[provider/Chrome]
enable = no

[provider/Firefox]
enable = no
