This was made primarily for myself, because there was not anything to help me automate the adding of iTunes metadata to 
the TV show files I was ripping. 

REQUIREMENTS:
- Branched version of atomicparsley (which can be downloaded from here: https://github.com/wez/atomicparsley)
- Media files named according to this naming convention '{show name} - S01E01'
- The tvdb_api for python (which can be downloaded from here: https://github.com/dbr/tvdb_api) -> They also have a renamer

USAGE:
- Set all of the paths before running the program
- If you use pushover, you can enter your user id and token to recieve push notifications when an error occurs
- example: python ~path/to/directory/Add_Meta.py How I Met Your Mother - S01E07.mp4

MISC:
- I paired this with Plex and Sickbeard to build an automated cloud DVR, that's what it was desgined for, so it
may not work for everybody. I'm happy to help if there are any questions, feel free to email me and I will get
back when I have time

