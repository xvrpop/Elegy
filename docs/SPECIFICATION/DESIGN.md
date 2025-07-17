# Design
Here we explain every feature to the detail. We specify what we want to implement and how.
We care about DX as much we care about the UX. Therefore we need to find a certain balance. We will try our best to keep the application performant and lightweight. But if we can significantly ease developing at the cost of some speed and space, we will do it. And performance apart, we want to provide an accessible experience to users, while still offering a high level of customization.

-----------------------------------------------------
## Core


### Cross-platform
We want to make Elegy available on popular OSs. Hence: Windows, macOS, Linux, Android, and iOS.

- Javascript
- HTML
- CSS (SCSS)

### Frameworks
- Electron (React)

### Databases & Storage
Describe how data is stored and managed.

### APIs & Integrations
List external services and how they connect.

### Infrastructure
Define hosting, servers, and deployment details.

## 5. System Design & Architecture

### High-Level Architecture
Provide an overview of system components.

### Data Flow & Components
Explain how information moves within the system.

### Security Considerations
Discuss authentication, encryption, and permissions.


-----------------------------------------------------
# Extensions


-----------------------------------------------------
## Features


### Wide support of audio formats
Ogg(Vorbis;Opus), MP3, MP4, M4A(AAC), ALAC, FLAC, WAV, and more.


### Syncing
Elegy should provide a serverless synchronization (over LAN or similar), or an Elegy server that hosts everything and allows for smooth sync, or even streaming.


### Synchronization
Provide synchronization of the settings and the music libraries.

decentrilized and serverless. Think of synchthing and LocalSend. /* (In case of conflicts we should provide a clear interface to resolve them) */
/* - **Settings synchroniation**: synchronize settings, and allow also to choose exactly what to sync. */


### Advanced tagging
MP3 tag3...

#### Download tags
From music.brainz, last.fm, ... 

#### Powerful tag parser 
Supporting tag is not enough. We need to support: multiple artist (with common separators, and user preferred ones);

#### Built-in tagging
Allow users to extensively tag their library, with autocomplete, smart templates, and powerful transforms (batch edit; find and replace, also with regex; convert tag types) [Check out onetagger](https://onetagger.github.io/)

#### ExTags
Elegy provides also it's own set of tagging for songs. Useful to specify things not possible inside of the standard tagging formats.


### DJ Mode 
Allow users (who tagged their library properly, lol) to define a random queue (shuffle) that follows several rules
  - Genres (multiple and mixed, or separated)
  - BPM
  - Similar songs
  - Artists
  - By sorting (prefer longer,shorter,most replayed, least replayed, etc.)


### Listening stats 
Analyze the user activity to provide statistics and precise data on: what, when, and how much they listen.


### Smart UX
By collecting user usage data we should aim to provide a customized experience (this is a vague idea)


### Extensions
We aim to provide a powerful extension SDK. Allowing more advanced users to customize their experience, and enrich it for the whole community (we will have to look into what license extensions devs should use). Extension should have the ability to control everything on Elegy (for sensitive task the user must approve each privilege. Like on android).


### Rearrange UI
Allow users to enter in "edit UI" mode, where they can create new tabs, arrange the layout how they want by moving elements around (this feature needs extensive explanations and developing)


### Advanced EQ
With frequency sliders with n bands; bass boost; ambience; stereo calibration; reverb; 


### VST effects 
[See FXsound](https://github.com/fxsound2/fxsound-app)


### Crossfade 
Crossfade of n sec, different curves, *and maybe we could add contextual fade based on the next song*


### Replaygain


### Gapless playback


### Advanced search 
Fuzzy search with filtering based on: genres; length; artists; album; etc.


### Save button 
set to which playlist this button will save the current song. Or simply choose in which playlists to add the song.


### Playlists
Not much to say. Just allow users to do set operations on their playlists. Export playlists (m3u8)


### Cinema mode
On PC, some beautiful theater mode themes provided as preinstalled extensions


### Full screen now playing on mobile
look into [Musicolet]()


### Rate songs
Personal editing stored for each track useful to get a customized experience


### Lyrics
Display lyrics and also provide a powerful editor for synched lyrics.
And also allow the user to download lyrics from lrcget.


### Plug lock
When the user plugs out their output device the music stops.


### Audio visualizers
Can a player be really cool without swag audio visualizers
The extension API should allow user to create audio visualizers on standard canvas, that we will integrate inside the player.
Imagine Avee Player, Milkdrop, etc. inside Elegy.


### Coverflow navigation (like ipod)
as extension


### Chromecast
Bring the experience also on the tv.


### Listen party
Create listening parties with serverless technology.
Collaborative queue, and synchronized listening (stop, skip, etc.).
