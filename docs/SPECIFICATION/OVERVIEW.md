# Overview
This document aim is to explain what is Elegy purpose.

Elegy<sup>1</sup> is a fully-featured music player. 
Our goal is to offer a practical, powerful, but also stunning interface.
Paired with a slick management of the music library and an audio experience of quality.

The aim of Elegy is ambitious. We want to design the **all-in-one** solution for managing a personal music experience.

We also want to give users full control over their experience. With not only extensive settings, but also a powerful extensions system.

And lastly, but probably one of the most important things: 

## Research
Our music player has to satisfy as many people we can. That's why our extension system is the most important part of the player.

Our target user goes from the amateur who likes to just listen to their unorganized library, to the expert who customizes the experience with tagging, playlists, EQs, etc.
People that have thousands of songs, and who love a fancy and customizable GUI.
Basically those outsiders who don't use streaming services, or use multiple and need a middle ground.

To summarize:
- Age ≈> 16
- Amateurs
- Audiophiles
- Who customizes their listening experience
- Who loves fancy GUIs
- People who don't use streaming services (at least not mainly).

Our "competitors" are many, both on desktop (which is where we focus for now), and on mobile:
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

We identify other music players, not to compete (even if it's inevitable), but to learn what we should or shouldn't do.

-----------------------------------------------------
## Notes
1. An [elegy](https://en.wikipedia.org/wiki/Elegy) could be vaguely defined as a lament. We chose this name not only because, in our opinion, it sounds good. But because we are unhappy with the current (as of 2025/03) state of open source music players.