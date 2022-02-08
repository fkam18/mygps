myGPS is a one page offline webapp for mobile to quickly store an event with GPS and timestamp offline
eventually it will push the locally stored events to server

You can try out using: https://v151.38cloud.com/mygps/

TOD
- show more human readable events rather than json (DONE)
- loc/lon to change to google map pointer (DONE)
- export to CSV/email  (see below)
- server push? (see below)
- might be wrap it as an Android webapp hence no need to browser it online to start with


Archiving Events
- finally implemented copy to clipboard then clear the local storage
- max events hard coded to 999 then self init (will change to an store error that sort)
- rationale: copy to clipboard then user decides if keep it in gmail or whatever; and no reliance on any smtp code or server push

