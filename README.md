# File-History
I have implemented a script whose purpose is to monitor a location and maintain a history of changes and accesses to it (directory structure). The history is composed of lines stored in a file, with each line having the following format: Datetime Operation ItemType Item.

Datetime: represents the date and time when the operation took place.
Operation: can be one of the following: create, access, write, delete.
ItemType: indicates the type of the item: directory or file.
Item: represents the absolute path of the item.
The project has been developed in two versions, with and without the use of the WatchDog module.
