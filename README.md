The Security Bible

[Forensics](#Forensics)


# Forensics
## Endpoint Forensics
### Windows Evidence of File / Folder Opening
> Open/Save MRU
- Registry key tracks files that have been opened or saved within a Windows shell dialog box including web browsers and most applications.
- NTUSER.DAT.

> Last-Visit MRU
- Tracks executable used by application to open files documented in Open/Save MRU
- shows the dir location for the last file that was accessed by that app.

> Recent Files
- Registry key tracks the last files and folders opened and is used to populate data in ‘recent’ menus. 
- NTUSER.DAT.

> Jump Lists
- Allows users to access frequently used items
- Data stored in AutomaticDestinations folder will each have a unique file prepended with the AppID of the association application and embedded with LNK files in each stream
- %UserProfile%

> Shell Bags
- Which folders were accessed on the local machine, network or removable device.
- Explorer access: USRCLASS.DAT
- Desktop Access: NTUSER.DAT

