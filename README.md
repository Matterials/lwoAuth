lwoAuth, a simple test server for the ALPHA version of LU.
This project is not related to; and is not DLU.
That said; anyone is welcome to work on this project.


I'm not taking this project as seriously as I take DLU -- this is just a side thing :P
(This is mostly just for fun and because I loved alpha LU)

This server has RakNet 3.25 included and can be compiled with Visual Studio 2017.

MySQL will also be required for compilation. It is, like RakNet, already included in this repo EXCEPT for the precompiled /lib/ folder.
This "lib" folder is in zip format inside of the "MySQL" folder. Simply extract that zip so you have a "lib" folder inside of the "MySQL" folder and you're set!
Do note that this precompiled version only works in Release mode!

Please note that this server is just for fun and should not be used to host a server for more than a few people!

To set up the MySQL database, just import the "lwo.sql" file present in the "MySQL" folder.
For now, the server expects the MySQL server to be on localhost, with root as username, lwo as database name, and a blank password.
(Unless if you recompile it yourself) This will be changed soon when .ini configuration is added.

For developers, a lot of the packet structure is different from live, so the currect docs from lcdr & humanoid, as helpful as they might be for live, they likely won't be of (that) much use to us as a lot of the netcode has changed since alpha.