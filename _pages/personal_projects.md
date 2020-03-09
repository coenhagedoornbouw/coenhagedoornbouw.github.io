

* [Streaming MP3 files from a NAS in Winamp](#streaming)<br>
* GUI automation with Python<br>
* Organizing photos with metadata<br>
* Creating QR codes from an IFC file<br>
* Using IFC as a Document Management System<br>
* Creating a folder structure from an Excel classification file<br>
* Getting and validing Quantities from an IFC file<br>

-------

# Streaming

Back in 2016 I bought a Western Digital NAS with 4TB of storage space. <br>
I have uploaded about 25GB of mp3 files on my NAS since then. <br>
I am still an avid Winamp user so I wanted to stream the mp3 files straight from my NAS into Winamp <br>

The first attempt was straighforward. I just tried to import a MP3 file from my NAS in Winamp. Hoping it would be that easy. Unfortunately no. It tried to establish a connection, but acces was denied. In retrospect logical because Winamp needed a user_id an authentication_token. 

The second attempt was using a different player than Winamp. I search the WD MyCloud forums and someone posted a link to the WD MyCloud Media player. It worked, but I was really dissapointed with the functionality, I was used to the queue and search functionality in Winamp. The WD MyCloud was a very basic media player. But it could stream my mp3 files. 

The option was in using m3u files. These are simple text files which are used to create playlists. 
There was an option in the WD MyCloud media player to save a playlist. I saved the playlist and openened it with notepad++
The WD MyCloud Mediaplayer stored my user_id and authenication_token in the m3 file.

I tried importing this playlist in Winamp and it worked! I am now happily streaming mp3 files from my NAS.

