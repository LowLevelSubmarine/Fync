# Fync
is a Tool for syncing all filesystems on  a portable memory device.

* First of all, Fync will do all its math with the files MD5 Hash so comparing databases should be easy.
* Fync should respect moved files and changed names.
* While syncing it is necessary that just the changed Files will be copied.



## File System
* TempStorage
    * Fync.jar
    * Fync.sync
    * Mirror
    * Data
* SolidStorage (including root storage)
    * FILES
    * Fync.cfg

### TempStorage -> Fync.jar
is the executable for controlling all the files

### TempStorage -> Fync.sync
contains the information related to the portable memory device / the executable.

### SolidStorage -> Mirror
stores the files of the root storage as hashes

### TempStorage -> Data
is a folder which should contain all the files that should be synced.

### SolidStorage -> FILES
is the anchor for all syncronisation. In the best case all storage spaces should look like the main storage.

### SolidStorage -> Fync.cfg
first of all declares the folder as fync storage space and contains all the information related to the storage space including weather the storage system is the root storage.
