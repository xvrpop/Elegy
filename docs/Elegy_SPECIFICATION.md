# Software Specification Document
This document aim is to explain Elegy nature and how it will be developed.
Every aspect regarding Elegy must be documented here, for now.

## 1. Introduction
[Elegy](#nr_elegy) is a fully-featured music player. 
One of its main objectives is to offer a practical, powerful, but also stunning interface.
Paired with a slick management of the music library and an audio experience of quality.

The scope of Elegy is ambitious. It’s designed to be the all-in-one solution for managing a personal music experience.

We also want to give users full control over their experience. With not only extensive settings, but also a powerful plugin system.

And lastly, but probably one of the most important things: Elegy is a software for the community. It uses a strong copyleft license (AGPLv3) to make this clear. But not only, the data about user usage is collected and processed locally (on user device). Therefore our philosophy is very clear: we take, we give, and we are transparent about it.

## 2. Overview & Research
Our music player has to sadisfy most users, but let's say that if you're searching for that nostalgic Y2K vibe poweramp gives: maybe Elegy isn't for you.

The target of Elegy is wide:
- Age ≈> 16
- From the amateur who likes to just listen to their unorganized library
- To the expert who customizes the experience with tagging, playlists, EQs, etc.
- Audiophiles
- People that have thousands of songs in their library
- Who loves fancy GUIs
- People who don't us streaming services (at least not mainly).

Our "competitors" are many, both desktop (which is where we focus for now), and on mobile:
- [Winamp](https://winamp.com/player)
- [MusicBee](https://www.getmusicbee.com/)
- [Foobar2000](http://www.foobar2000.org/)
- [AIMP](https://www.aimp.ru/)
- [Clementine](https://www.clementine-player.org/)
- [Strawberry](https://www.strawberrymusicplayer.org/)
- [Audacious](http://audacious-media-player.org/)
- [MediaMonkey](http://www.mediamonkey.com/)
- [DeaDBeeF](https://deadbeef.sourceforge.io/)
- [RhythmBox](https://wiki.gnome.org/Apps/Rhythmbox)
- [Amarok](https://amarok.kde.org/)
- [Quod Libet](https://quodlibet.readthedocs.org/en/latest/)
- [Dopamine](https://digimezzo.github.io/site/software)
- [Crates](https://crates.app/)
- [Elisa](https://apps.kde.org/elisa)
- [Rune Player](https://rune.not.ci/)
- [Tauon Music Box](https://tauonmusicbox.rocks/)
- [GNOME Music](https://wiki.gnome.org/Apps/Music)
- [Museeks](http://museeks.io/)
- [Amberol](https://gitlab.gnome.org/ebassi/amberol)
- [Madsonic](http://www.madsonic.org/)
- [Nora](https://noramusic.netlify.app/)
- [Lollypop](https://gitlab.gnome.org/World/lollypop)
- [Plexamp](https://www.plex.tv/plexamp/)
- [Roon](https://roon.app/)
- [Walkstar](https://www.cromulentlabs.com/walkstar/)
- [XMPlay](https://www.un4seen.com/xmplay.html)
- [Vox Music Player](https://vox.rocks/)
- [Sayonara](https://sayonara-player.com/)
- [Guayadeque](https://www.guayadeque.org/)
- [Musicolet](https://krosbits.in/musicolet/)
- [Oto Music](https://play.google.com/store/apps/details?id=com.piyush.music&hl=it)
- [GoneMAD](https://gonemadmusicplayer.blogspot.com/)
- [Poweramp](https://powerampapp.com/it/)
- [Fossify Music Player](https://github.com/FossifyOrg/Music-Player)
- [Vanilla Music](https://github.com/vanilla-music/vanilla)
- [Vinyl Music Player](https://github.com/VinylMusicPlayer/VinylMusicPlayer)
- [Phiola](https://github.com/stsaz/phiola)
- [Harmony Music](https://github.com/anandnet/Harmony-Music)
- [ClassiPod](https://adeeteya.github.io/Classipod/)
- [Vibe You](https://you-apps.net/)
- [Soul Searching](https://github.com/enteraname74/SoulSearching)
- [Gramophone](https://github.com/AkaneTan/Gramophone)
- [Music Player Lite](https://github.com/AP-Atul/music_player_lite)
- [Phocid](https://sunsetware.org/phocid)
- [AntiiQ](https://codeberg.org/coleblvck/AntiiQ)
- [MonsterMusic](https://github.com/ZTFtrue/MonsterMusic)
- [mucke](https://github.com/moritz-weber/mucke)
- [The Phoenix Project](https://github.com/shaan-mephobic/The-Phoenix-Project)
- [Namida](https://github.com/namidaco/namida)
- [Music Player GO](https://github.com/enricocid/Music-Player-GO)
- [Groovy - Music Player](https://play.google.com/store/apps/details?id=com.bitmavrick.groovy)
- [Eon Music Player](https://play.google.com/store/apps/details?id=qijaz221.github.io.musicplayer&hl=it)
- [Spotube](https://github.com/KRTirtho/spotube)
- [Koel](https://github.com/koel/koel)
- [Nuclear](https://github.com/nukeop/nuclear)
- [Harmonoid](https://github.com/harmonoid/harmonoid)
- [Taon](https://github.com/Taiko2k/Tauon)
- [Symphony](https://github.com/zyrouge/symphony)
- [Mooonsync](https://github.com/Moosync/Moosync)
- [Swingmusic](https://github.com/swingmx/swingmusic)
- [MissingCore Music](https://github.com/MissingCore/Music)

We identify other music players, not to compete (even if its obviously inevitable), but to learn what we should or shouldn't do.

## 3. Requirements & Features

### Functional Requirements

- **Cross-platform**: we want, even it will take time, to make Elegy available on popular OSs. Hence: Windows, macOS, Linux, Android, and iOS. 
- **Wide support of audio formats**: Ogg(Vorbis;Opus);MP3(); MP4(); M4A(AAC); ALAC; FLAC; WAV
- **Synching**: Elegy should provide a serverless synchronization (over LAN or similar), or an Elegy server that hosts everything and allows for smooth sync, or even streaming.
- **Library synchronization**: over LAN/Bluetooth. (In case of conflicts we should provide a clear interface to resolve them)
- **Settings synchroniation**: synchronize settings, and allow also to choose exactly what to sync.
- **Wide tag support**: *list various tag headers**.
- **Powerful tag parser**: supporting tag is not enough. We need to support: multiple artist (with common separators, and user preffered ones);
- **Built-in tagging**: allow users to extensively tag their library, with autocompletition, smart templates, and powerful transforms (batch edit; find and replace, also with regex; convert tag types) [Check out onetagger](https://onetagger.github.io/)
- **DJ Mode**: allow users (who tagged their library properly, lol) to define a random queue (shuffle) that follows several rules
  - Genres (multiple and mixed, or separated)
  - BPM
  - Similar songs
  - Artists
  - By sorting (prefer longer,shorter,most replayed, least replayed, etc.)
- **Listening stats**: analyze the user activity to provide statistics and precise data on: what, when, and how much they listen.
- **Smart UX**: by collecting user usage data we should aim to provide a customized experience (this is a vague idea)
- **Extensions**: we aim to provide a powerful extension SDK. Allowing more advanced users to customize their experience, and enrich it for the whole community (we will have to look into what license extensions devs should use). Extension should have the ability to control everything on Elegy (for sensitive task the user must approe each privilige. Like on android).
-  **Rearrange UI**: allow users to enter in "edit ui" mode, where they can create new tabs, arrange the layout how they want by moving elements around (this feature needs extensive explanations and developing)
-  **Advanced EQ**: with frequency sliders with n bands; bass boost; ambience; stereo calibration; reverb; *VST effects*. [See FXsound](https://github.com/fxsound2/fxsound-app)
-  **Crossfade**: crossfade of n sec, different curves, *and maybe we could add contextual fade based on the next song*
-  **Replaygain**
-  **Gapless playback**
-  **Advanced search**: fuzzy search with filtering based on: genres; length; artists; album; etc.
-  **Save button**: set to which playlist this button will save the current song. Or simply choose in which playlists to add the song.
-  **Playlists**: not much to say. Just allow users to do set operations on their playlists. Export playlists (m3u8)
-  **Cinema mode**: on PC, some beatiful theater mode themes provided as preinstalled extensions
-  **Full screen now playing on mobile**: look into [Musicolet]()
-  **Rate songs**: personal editing stored for each track useful to get a customized experience
-  **Display and Edit synched (or not) lyrics**
-  **Dowload tags**+lyrics from providers like: music.brainz; last.fm; LRCGET
-  **Start/Stop music on device plug in/out**
-  **Music visualizers** as extension
-  **Coverflow navigation (like ipod)** as extension
-  **Chromecast**
- **Listen party (serverless)** *lol is this even possible*


### Non-Functional Requirements
We care about developing confortability as much we care about the UX. Therefore we need to find a certain balance. We will try our best to keep the application sie as small as we can. But if we can ease developing at the cost of some MB we will do it. What we think should be actually important is the performance of the app itself. Speed and resource usage will be our focus.

And performance apart, we want to provide a very intuitive experience to users, without limiting powerusers.
It will be challanging, but otherwise we wouldn't do it!


## 4. Technology Stack

### Programming Languages & Frameworks
Explain chosen languages and frameworks.

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

## 6. Development & Project Plan

### Phases & Milestones
Outline project stages and timelines.

### Risks & Challenges
Identify potential problems and mitigation strategies.

### Testing Strategy
Explain testing methods, including automation and manual tests.

## 7. Notes & References
- [An elegy could be vaguelzy defined as a lament. We chose this name not only because, in our opinion, it sounds good. But because we are unhappy with the current (as of 2025/03) state of open source music players.](https://en.wikipedia.org/wiki/Elegy){#nr_elegy}

[](){#nr_}
