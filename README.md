# DJ-Organizer

## This is a GitHub Repository for the development of a DJ-Organization Tool for DIDA 425

## Project Idea 
<hr>
* User Visits webpage (hosted on github pages)
* User Accesses their spotify account using O-Auth
* User selects playlist from their spotify library 
* Use Open Source Tool to convert spotify playlist to Raw Audio Files (found spotDL - CL software, may have issues if not a spotify premium user, also found https://lucida.to/ or other possibilities at https://fmhy.net/audio)
* Use Open Source Tool (potentially 'EchoNest') to extract audio features from audio files
* Using these audio features develop a collaborative filtering / recommendation system
* Use the collaborative filtering system to obtain similarity scores between songs and find the ordering which minimizes the total similarity differences between songs
* Output an ordered list of songs, and convert this list back into a spotify playlist and allow user to import it back into Spotify 

