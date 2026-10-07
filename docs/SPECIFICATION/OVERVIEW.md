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

| App                                                                                                    | Windows | Linux | MacOS | Android | iOS | Web | Open Source | Price    |
| ------------------------------------------------------------------------------------------------------ | :-------: | :-----: | :-----: | :-------: | :---: | :---: | :-----------: | :--------: |
| [Winamp](https://winamp.com/player)                                                                    | ⚠       | ✖     | ✖     | ✔       | ✔   | ✖   | ✖           | Freemium |
| [MusicBee](https://www.getmusicbee.com/)                                                               | ✔       | ✖     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Foobar2000](http://www.foobar2000.org/)                                                               | ✔       | ✖     | ✔     | ✔       | ✔   | ✖   | ✖           | Free     |
| [AIMP](https://www.aimp.ru/)                                                                           | ✔       | ✔     | ✖     | ✔       | ✖   | ✖   | ✖           | Free     |
| [Clementine](https://www.clementine-player.org/)                                                       | ✔       | ✔     | ✔     | ⚠       | ✖   | ✖   | ✔           | Free     |
| [Strawberry](https://www.strawberrymusicplayer.org/)                                                   | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Audacious](http://audacious-media-player.org/)                                                        | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [MediaMonkey](http://www.mediamonkey.com/)                                                             | ✔       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [DeaDBeeF](https://deadbeef.sourceforge.io/)                                                           | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [RhythmBox](https://wiki.gnome.org/Apps/Rhythmbox)                                                     | ✖       | ✔     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Amarok](https://amarok.kde.org/)                                                                      | ✖       | ✔     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Quod Libet](https://quodlibet.readthedocs.org/en/latest/)                                             | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Dopamine](https://digimezzo.github.io/site/software)                                                  | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Crates](https://crates.app/)                                                                          | ✔       | ✖     | ✔     | ✔       | ✔   | ✖   | ✖           | Freemium |
| [Elisa](https://apps.kde.org/elisa)                                                                    | ✔       | ✔     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Rune Player](https://rune.not.ci/)                                                                    | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Paid     |
| [Tauon Music Box](https://tauonmusicbox.rocks/)                                                        | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [GNOME Music](https://wiki.gnome.org/Apps/Music)                                                       | ✖       | ✔     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Museeks](http://museeks.io/)                                                                          | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Amberol](https://gitlab.gnome.org/ebassi/amberol)                                                     | ✖       | ✔     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Madsonic](http://www.madsonic.org/)                                                                   | ✔       | ✖     | ✖     | ✔       | ✔   | ✖   | ✔           | Freemium |
| [Nora](https://noramusic.netlify.app/)                                                                 | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Lollypop](https://gitlab.gnome.org/World/lollypop)                                                    | ✖       | ✔     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Plexamp](https://www.plex.tv/plexamp/)                                                                | ❔       | ❔     | ❔     | ❔       | ❔   | ✖   | ❔           | ❔        |
| [Roon](https://roon.app/)                                                                              | ✔       | ✔     | ✔     | ✔       | ✔   | ✖   | ⚠           | Paid     |
| [Walkstar](https://www.cromulentlabs.com/walkstar/)                                                    | ✖       | ✖     | ✖     | ✖       | ✔   | ✖   | ✖           | Free     |
| [XMPlay](https://www.un4seen.com/xmplay.html)                                                          | ✔       | ✖     | ✖     | ✖       | ✖   | ✖   | ✖           | Free     |
| [Vox Music Player](https://vox.rocks/)                                                                 | ✔       | ✖     | ✔     | ✖       | ✔   | ✖   | ✖           | Freemium |
| [Sayonara](https://sayonara-player.com/)                                                               | ✖       | ✔     | ✖     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Musicolet](https://krosbits.in/musicolet/)                                                            | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [Oto Music](https://play.google.com/store/apps/details?id=com.piyush.music&hl=it)                      | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [GoneMAD](https://gonemadmusicplayer.blogspot.com/)                                                    | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [Poweramp](https://powerampapp.com/it/)                                                                | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [Fossify Music Player](https://github.com/FossifyOrg/Music-Player)                                     | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Vanilla Music](https://github.com/vanilla-music/vanilla)                                              | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Vinyl Music Player](https://github.com/VinylMusicPlayer/VinylMusicPlayer)                             | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Phiola](https://github.com/stsaz/phiola)                                                              | ✔       | ✔     | ✔     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Harmony Music](https://github.com/anandnet/Harmony-Music)                                             | ✔       | ✔     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [ClassiPod](https://adeeteya.github.io/Classipod/)[2](https://github.com/adeeteya/Classipod)           | ✖       | ✖     | ✖     | ✖       | ✖   | ✔   | ✔           | Free     |
| [Vibe You](https://you-apps.net/)[2](https://github.com/you-apps/VibeYou)                              | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Soul Searching](https://github.com/enteraname74/SoulSearching)                                        | ✔       | ✖     | ✖     | ✔       | ✖   | ✔   | ✔           | Free     |
| [Gramophone](https://github.com/AkaneTan/Gramophone)                                                   | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Music Player Lite](https://github.com/AP-Atul/music_player_lite)                                      | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Phocid](https://sunsetware.org/phocid)                                                                | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [AntiiQ](https://codeberg.org/coleblvck/AntiiQ)                                                        | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [MonsterMusic](https://github.com/ZTFtrue/MonsterMusic)                                                | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [mucke](https://github.com/moritz-weber/mucke)                                                         | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [The Phoenix Project](https://github.com/shaan-mephobic/The-Phoenix-Project)                           | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Music Player GO](https://github.com/enricocid/Music-Player-GO)                                        | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Groovy - Music Player](https://play.google.com/store/apps/details?id=com.bitmavrick.groovy)           | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [Eon Music Player](https://play.google.com/store/apps/details?id=qijaz221.github.io.musicplayer&hl=it) | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✖           | Freemium |
| [Spotube](https://github.com/KRTirtho/spotube)                                                         | ✔       | ✔     | ✔     | ✔       | ✔   | ✖   | ✔           | Free     |
| [Koel](https://github.com/koel/koel)                                                                   | ✖       | ✖     | ✖     | ✔       | ✔   | ✔   | ✔           | Free     |
| [Harmonoid](https://github.com/harmonoid/harmonoid)                                                    | ✔       | ✔     | ✔     | ✔       | ✔   | ✖   | ✔           | Free     |
| [Taon](https://github.com/Taiko2k/Tauon)                                                               | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Symphony](https://github.com/zyrouge/symphony)                                                        | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Mooonsync](https://github.com/Moosync/Moosync)                                                        | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Swingmusic](https://github.com/swingmx/swingmusic)                                                    | ✖       | ✖     | ✖     | ✔       | ✖   | ✔   | ✔           | Free     |
| [MissingCore Music](https://github.com/MissingCore/Music)                                              | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Namida](https://github.com/namidaco/namida)                                                           | ✔       | ⚠     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Nuclear](https://github.com/nukeop/nuclear)                                                           | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Audion](https://github.com/dupitydumb/Audion)                                                         | ✔       | ✔     | ✔     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Sonora](https://github.com/sonorahq/sonora)                                                           | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Parachord](https://github.com/Parachord/parachord)                                                    | ✔       | ✔     | ✔     | ✖       | ✖   | ✖   | ✔           | Free     |
| [Kopuz](https://github.com/Kopuz-org/kopuz)                                                            | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [BitChord](https://github.com/kushagrasinghx/BitChord)                                                 | ⚠       | ⚠     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [SpatialFlow](https://github.com/MythicalSHUB/SpatialFlow)                                             | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |
| [Pixel Player](https://github.com/PixelPlayerHQ/PixelPlayerOSS)                                        | ✖       | ✖     | ✖     | ✔       | ✖   | ✖   | ✔           | Free     |


We identify other music players, not to compete (even if it's inevitable), but to learn what we should or shouldn't do.

-----------------------------------------------------
## Notes
1. An [elegy](https://en.wikipedia.org/wiki/Elegy) could be vaguely defined as a lament. We chose this name not only because, in our opinion, it sounds good. But because we are unhappy with the current (as of 2025/03) state of open source music players.