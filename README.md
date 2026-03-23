
## ARGUS CLASSIC - SERVER GUIDE
## World of Warcraft 1.12.1 (Vanilla)


## [ OVERVIEW ]

Argus Classic is a custom Vanilla (1.12.1) WoW server.
This guide explains how to install, start, and properly stop
the server.

## [ INSTALLATION ]

## (1) CLIENT SETUP

You will need your own copy of the 1.12.1 World of Warcraft Client
Copy patch-s.mpq Into World of Warcraft\Data\
Then copy realmlist.wtf Into Your WoW root folder (where Wow.exe is located)

## (2) DATABASE

Go to the "database" folder and run: "start-server.bat".
This starts the database service.

## (3) SERVER STARTUP

Go to the "install" folder and start in this order:

1. realmd.exe        (Authentication server)
2. mangosd.exe       (World server)

## [ FIRST LAUNCH NOTE ]

The first startup may take several minutes. This is normal (bot initialization). Next launches will be much faster.

A GM account is already created

Login : Admin
Password : Admin

## [ IMPORTANT - SHUTDOWN PROCEDURE ]

Do NOT close windows using the "X".

Recommended method:

1. In-game chat: type with your character .server shutdown 0 (or: .ser shut 0)
2. Close WoW normally
3. Wait for mangosd.exe to close automatically
4. In realmd.exe: Ctrl + C
5. In database window: Ctrl + C, Then press: o

## [ NOTES ]

Following this procedure prevents data corruption and ensures
a clean shutdown.
