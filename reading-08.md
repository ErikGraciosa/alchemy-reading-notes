Good read about local storage. The example with the same was nice to see and manipulate the pieces with local storage open. 
The reasoning makes sense to avoid slowing down pages and prevent data from being sent back and forth from server to client multiple times. 
It was nice that the author emphasized the reason for the article in a weird bullet point sentence thing about local storage, 
what we really want:
a lot of storage space
on the client
that persists beyond a page refresh
and isn’t transmitted to the server
Some history about using third party browser plug ins before local storage. 
The author also recommends using Modernizr to detect local storage available. 
The local storage for most browsers is capped at 5Mb unless a user changes storage quota, as of 2011.  
Some description about using a check if game exists in local storage before loading a fresh game probably translates to most sites using local storage
to first check for presence before loading defaults. Some version of SQL vs indexedDB for more storage is the future back in 2011.
