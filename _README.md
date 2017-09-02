# hydrone
A nodejs web server that pulls RFID and GPS info from a drone over bluetooth.

A drone flies around collecting RFID tag info and logs GPS latitude and longitude when it find a tag, then flies back to home base where it connects with a computer running this server over bluetooth. Tag locations and info are then displayed on a google map.
