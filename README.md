# Fync
is a Tool for syncing all filesystems on  a portable memory device.

* First of all, Fync will do all its math with the files MD5 Hash so comparing databases should be easy.
* Fync should respect moved files and changed names.
* While syncing it is necessary that just the changed Files will be copied.



## File System
* Memory device
    * Fync.jar
    * Fync.sync
    * FyncData
* Main storage
    * FILES
        * Fync.cfg
* Storage 1 (2, 3, ...)
    * FILES
        * Fync.cfg

### Fync.jar
is the executable for controlling all the files

### Fync.cfg
first of all declares the folder as fync storage space and contains all the information related to the storage space.

### Fync.sync
contains the information related to the portable memory device / the executable.

### FyncData
is a folder which should contain all the files that should be synced.


## Main Storage
is the anchor for all syncronisation. In the best case all storage spaces should look like the main storage.

## Portable Memory
stores the raw construct of the main storage plus the hashes of all files
